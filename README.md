# Fichaje

PWA responsive de control horario para móvil y escritorio.

## V0.1
- Fichaje de entrada/salida y descansos (demo local)
- Dashboard responsive inspirado en el mockup aprobado
- ES / CA / EN
- Estructura preparada para Supabase
- Manifest PWA

## Desarrollo
```bash
npm install
npm run dev
```

## Supabase
Copia `.env.example` a `.env.local` y configura URL y anon key. La siguiente fase conecta autenticación, empresas, empleados, fichajes, auditoría y RLS.

> Importante: el fichaje actual es una demo de interfaz. Antes de producción la hora oficial, eventos y auditoría deben persistirse en backend y aplicarse políticas RLS.

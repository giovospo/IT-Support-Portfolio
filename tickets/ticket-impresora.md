# Ticket: Impresora no imprime

## Problema
El usuario no puede imprimir documentos.

## Diagnóstico

1. Verificar conexión (USB o red)
2. Revisar cola de impresión
3. Validar estado de impresora

## Solución

1. Reiniciar servicio de impresión
   net stop spooler
   net start spooler

2. Limpiar cola
3. Reinstalar driver

## Resultado
✅ Impresión restablecida
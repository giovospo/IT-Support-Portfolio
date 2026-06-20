# Ticket: Usuario sin conexión a internet

## Problema
El usuario reporta que no tiene acceso a internet.

## Diagnóstico paso a paso

1. Verificar conexión física
   - Revisar cable o conexión WiFi ✅

2. Ejecutar comandos
   ipconfig
   ping google.com

3. Probar conectividad por IP
   ping 8.8.8.8

4. Identificar problema:
   - Si responde a IP pero no a dominio → DNS ❌

## Solución

1. Configurar DNS manual:
   8.8.8.8
2. Reiniciar adaptador de red
3. Verificar conexión nuevamente

## Resultado
✅ Internet restaurado
## 📝 Enumeración 

Este proyecto de Windows Forms en C# demuestra cómo utilizar un `enum` para representar diferentes estados de un pedido y mostrarlos en un `ComboBox`. El usuario puede seleccionar un estado y visualizar un mensaje descriptivo correspondiente al estado seleccionado.

### 🚀 Funcionalidades Principales

- Carga automática de los valores del `enum EstadoPedido` en un `ComboBox`.
- Permite al usuario seleccionar un estado del pedido.
- Muestra un mensaje personalizado al presionar el botón **Mostrar**, según el estado elegido.

### 📋 Enum utilizado

```csharp
enum EstadoPedido
{
    Pendiente,
    Procesando,
    Enviado,
    Entregado,
    Cancelado
}
```
🖼️ Interfaz
- ComboBox: muestra los distintos estados del pedido.
- Button (btnMostrar): al hacer clic, evalúa el estado seleccionado.
- Label (lblResultado): muestra un mensaje según el estado del pedido.

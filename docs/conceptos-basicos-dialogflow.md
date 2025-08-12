## Introducción

Este documento expone algunos de los conceptos básicos que conforman la plataforma **Dialogflow**, los cuales permitirán hacer un uso efectivo de esta herramienta para crear un agente de interpretación de lenguaje natural que esté en capacidad para prestar servicio al cliente en WTF, así como servir de ayuda para transferir un conocimiento teórico sobre la herramienta.

## Conceptos básicos de Dialogflow

### Agentes virtuales:
Son los engargados de manejar conversaciones con los usuarios finales. Los agentes se construyen para manejar un tipo de conversación relacionada con tu sistema o con las reglas de negocio del mismo.

Los agentes son similares a un agente de call center humano: Necesitas capacitar (o entrenar) a un agente telefónico de servicio al cliente para que atienda los requerimientos de tu negocio de forma efectiva. El entranamiento no tiene que ser totalmente explícito en todos sus detalles, ya que un agente de servicio al cliente adquiere cierta **autonomía** conforme el paso del tiempo, por lo que aprenderá a manejar mejor sus conversaciones.

### Intentos (Intents):

Los intentos son mecanismos de los que dispone Dialogflow, y permiten **categorizar la intención** de un usuario final dentro de una conversación. Es decir: Los intents permiten detectar o identificar **qué es lo que quiere el usuario**, o qué es lo que solicita. Los intents permiten clasificar lo que el usuario quiere mediante lo que se conoce como una **expresión de usuario final** o *end-user expression*.

### Partes básicas de un Intent: 

**1. Frases de entrenamiento:** Son frases de ejemplo de lo que los usuarios finales podrían decirle al agente. Cuando un usuario final escribe algo que se asemeja a alguna de las frases de ejemplo, Dialogflow hará coincidir la expresión de usuario final con la intención asociada a dicha expresión.

**2. Acción:** Es posible definir una acción por cada intent. Cuando Dialogflow hace coincidir un intent, le puede proporcionar a nuestro sistema la acción determinada. Es posible disparar acciones concretas de nuestro sistema por medio de las acciones proporcionadas por Dialogflow.

**3. Parámetros:** Los parámetros son datos que Dialogflow extrae de una expresión de usuario final. Los parámetros se caracterizan porque tienen un **tipo asociado**, lo que se conoce como **tipo de entidad**. El tipo de entidad indica cómo será tratada la información de cada parámetro (ejemplo: como una fecha, como un número, etc...). También es posible definir **tipos de entidad personalizados**.

**4. Respuestas:** Es toda aquella información que, como su nombre indica, responde el agente. Las respuestas pueden parametrizarse de manera que generen una **continuidad en la conversación**, por lo que podrían ser de diferentes tipos: Respuesta concreta, respuesta con preguntas para obtener más información del usuario, respuesta para finalizar la conversación, etc.

### Entidades (Entities):

Las entidades son tipos de datos que crea Dialogflow para representar datos contenidos en una expresión de usuario final. Podría decirse que son **objetos** que representan datos de la expresión del usuario. Por ejemplo: una fecha, un nombre, una talla, un precio, etc.

### Contextos:

Como en una conversación entre humanos, se requiere un contexto para entenderla. Dialogflow también necesita contextos para manejar el flujo de las conversaciones de forma dinámica.

El contexto es toda aquella información que el agente necesita saber para dar continuidad y flujo a una conversación con el usuario final. En Dialogflow es posible definir contextos para un intent, estableciendo **contextos de entrada** y **contextos de salida**.


























# Metodología SAPITS

## 🔒 Valores y Principios

### 1. Seguridad
La seguridad de tus datos es lo MÁS importante para SAPITS y por eso queremos explicarte cómo lo hacemos.

- **Discos Duros Encriptados**: Utilizamos LUKS1/LUKS2 para el cifrado completo de discos duros, asegurando que incluso si alguien accede físicamente a los discos, no podrá acceder a los datos almacenados en los equipos de cómputo dedicados exclusivamente a SAPITS.

- **Sistema Operativo Seguro**: QubesOS es nuestro sistema operativo predeterminado, ofreciendo un aislamiento privado y seguro para cada etapa del proceso, gozando de la máxima seguridad posible para tus datos.

- **Modelo de Contraseñas**: [Sin Implementar] Estamos desarrollando un sistema descentralizado para la gestión de contraseñas de discos duros e inicio de sesión, evitando la centralización de acceso y reduciendo riesgos de corrupción o amenazas a la seguridad.

- **Mensajería con Encriptación E2E**: Utilizamos tecnologías de vanguardia para proporcionar siempre seguridad entre SAPITS y sus usuarios. SimpleX Chat es una de las apps de mensajería más revolucionarias del momento, sin requerir de un número de teléfono o correo electrónico para su uso, cuenta con encriptación de extremo a extremo (E2E) para proteger sus conversaciones, además de contar con servidores descentralizados E2E y con la posibilidad de usar perfiles incógnitos para su anonimato.

### 2. Anonimato

#### 2.1 Fundamentos Filosóficos
El anonimato en SAPITS no es solo una característica técnica, sino un principio filosófico fundamental. Reconocemos que en un mundo cada vez más vigilado, el derecho a la privacidad se ha convertido en una necesidad básica.

#### 2.2 Libertad de Expresión y Protección de Identidad

##### Principios Fundamentales

- **Ausencia de Interacción Humana Directa**:
  - El modelo SAPITS elimina la posibilidad de discriminación interpersonal al no requerir contacto Humano-Humano en ningún punto del servicio.
  - Los sistemas automatizados están diseñados para ser completamente neutrales, sin capacidad para juzgar o discriminar basándose en características personales.

- **Derecho al Anonimato**:
  - Los usuarios tienen derecho absoluto a proteger su identidad mediante cualquier medio de su elección.
  - La vestimenta, incluyendo elementos que cubran el rostro o cuerpo, no puede ser motivo de denegación de servicio.

- **Uso de TOR**:
  - Los usuarios siempre podrán usar el [protocolo de Tor](https://orbot.app/es_CU/) para poder ocultar su IP mientras se interactúa en SimpleX Chat.
  - El uso de Tor es altamente recomendado para mejorar la privacidad y el anonimato en línea.
  - También es posible usar una VPN privada, segura y transparente como [Mullvad VPN](https://mullvad.net/es/vpn) o [Proton VPN](https://protonvpn.com/es-419/free-vpn/server).
  - Enlaces .onion: [Mullvad VPN](http://o54hon2e2vj6c7m3aqqu6uyece65by3vgoxxhlqlsvkmacw6a7m7kiad.onion/es/vpn).

##### Consideraciones sobre Vigilancia

1. **Uso de Cámaras**:
   - **Cumplimiento Legal**: En jurisdicciones donde sea obligatorio el uso de cámaras de vigilancia:
     - Se implementarán las mínimas necesarias para cumplir con la ley
     - Se señalizará claramente su presencia
     - Las grabaciones se manejarán con los más altos estándares de privacidad
   
   - **Protección de Datos**:
     - Las grabaciones se almacenarán cifradas.
     - Acceso restringido únicamente a personal autorizado.
     - Tiempo de retención mínimo legalmente requerido.

2. **Derechos del Usuario**:
   - **Ante la presencia de cámaras**:
     - Los usuarios mantienen su derecho a cubrirse el rostro y cuerpo.
     - No se puede denegar el servicio por ejercer este derecho.
     - Las grabaciones no pueden ser utilizadas para identificar usuarios sin orden judicial.

   - **En ausencia de cámaras**:
     - Los mismos derechos de privacidad y anonimato se mantienen.
     - La vestimenta no puede ser motivo de sospecha o rechazo.

3. **No Discriminación**:
   - **Prohibición expresa** de negar el servicio basado en:
     - Elección de vestimenta o cobertura facial.
     - Apariencia física.
     - Cualquier característica personal percibida.

   - **Protección contra perfiles**:
     - Los sistemas de SAPITS no generan perfiles basados en apariencia.
     - No se utilizan sistemas de reconocimiento facial o biométricos.
     - No se almacenan datos que permitan la identificación personal.

#### 2.3 Sistema de Identificación Anónima [Parcial]

##### Consideraciones de Diseño

- **Dilemas de implementación**:
  - Equilibrio entre utilidad y privacidad.
  - Experiencia del usuario vs. Seguridad.
  - Resistencia a la censura.

#### 2.4 Hoja de Ruta Futura

##### Próximos Pasos

1. **Fase de investigación**
2. **Desarrollo de prototipos**
3. **Programa de recompensas**

#### 🔐 Propuesta Técnica

#### 1️⃣ Sistema de Identificación Principal

**Generación de ID y PIN Base**

- Cada usuario recibe:
  - Un identificador único, aleatorio y anónimo (ID).
  - Un PIN base aleatorio de 8 dígitos.
  
**Características por Establecimiento**

- Generación local: Cada establecimiento SAPITS genera sus propios IDs y PINs.
- Independencia: Se requiere un nuevo ID y PIN para cada establecimiento SAPITS.
- Modo invitado: Visualización del catálogo de productos y servicios sin necesidad de ID/PIN.

**Proceso de Uso**

1. El usuario recibe su ID y PIN al iniciar.
2. No se vincula con información personal.
3. Se requiere ID y PIN válidos para acceder a servicios.

> 📝 **Nota de Seguridad**: Recomendamos guardar el ID y PIN de forma segura:
>
> - En papel físico
> - En un gestor de contraseñas de confianza

#### 2️⃣ Sistema de PINs Temporales

**Características Principales**

- Generación: Un PIN único por cada servicio/producto solicitado.
- Propósito: Autenticación de transacciones específicas.
- Protección: No compromete la contraseña base.

**Vinculación y Seguridad**

- Asociación directa con el servicio solicitado.
- Conexión segura entre ID del cliente y servicio.
- Prevención de fraudes y suplantación de identidad.

**Beneficios Operativos**

- Eficiencia: Permite a técnicos trabajar sin intervención presencial del usuario.
- Rapidez: Agiliza la entrega de servicios/productos.
- Seguridad: Minimiza tiempo de permanencia en el establecimiento.

**Medidas de Protección**

- Prevención de:
  - Vulnerabilidades.
  - Robos.
  - Actos terroristas.
  - Secuestros.
  - Otros riesgos asociados.

> ⚠️ **Nota Importante**: Los PINs temporales:
>
> - Tienen duración limitada.
> - Se invalidan automáticamente tras su uso.
> - No pueden reutilizarse.

### 3. Privacidad

#### 3.1 Principios de Privacidad

1. **¿Qué es la privacidad?**
   - La privacidad es el derecho fundamental de los individuos a controlar su información personal y decidir cómo se recopila, utiliza y comparte.
   - A menudo se confunde la privacidad en contraste con el anonimato pero aunque sean conceptos muy relacionados es importante diferenciarlos. La privacidad se refiere al control sobre la información personal, mientras que el anonimato se refiere a la capacidad de ocultar la identidad.

2. **Minimización de Datos**:
   - Solo se recopilarán los datos estrictamente necesarios para proporcionar el servicio.
   - Se evitará la recopilación de datos sensibles a menos que sea absolutamente necesario.

3. **Transparencia**:
   - Los usuarios serán informados sobre qué datos se recopilan y con qué propósito.
   - Se proporcionarán opciones para que los usuarios gestionen sus preferencias de privacidad.

4. **Control del Usuario**:
   - Los usuarios tendrán la capacidad de acceder, modificar o eliminar sus datos personales.
   - Se implementarán mecanismos para que los usuarios puedan ejercer sus derechos de privacidad de manera efectiva.

## 🔍 Proceso

### Fase Inicial

#### Usuario

1. **Necesidad**: El usuario requerirá un servicio informático el cual podría llegar a consistir en muchos servicios disponibles (dependiendo del establecimiento SAPITS) como reparación, mantenimiento de equipo de cómputo, compra y venta de diferentes productos, etc.

2. **Opciones**: El usuario obviamente tendrá múltiples opciones de diferentes establecimientos incluyendo los que no están en el protocolo de SAPITS, aquellos usuarios más maximalistas en cuanto en la privacidad y seguridad de sus datos podrían llegar a considerar adquirir un servicio de un establecimiento SAPITS en vez de uno común y corriente.

3. **Contacto**: Los métodos de contacto pueden variar dependiendo de cada establecimiento SAPITS pero TODOS deberán usar al menos [SimpleX Chat](https://simplex.chat/es/) ([SimpleX Chat .onion](http://isdb4l77sjqoy2qq7ipum6x3at6hyn3jmxfx4zdhc72ufbmuq4ilwkqd.onion/es/)) como método de contacto principal.

#### Establecimiento

1. **Preparación**: Para este punto, el establecimiento ya debe tener un lugar físico y un equipo técnico capacitado para brindar el servicio. Además de tener ya definidas las herramientas de Contacto para poder empezar una comunicación con el cliente.

  - Se debe contar con:

    - Uno o varios equipos de cómputo con QubesOS instalado.
    - Canales de comunicación ya listos y publicitados para permitir al usuario consultar al establecimiento en cuestión.
    - Equipo técnico con el nivel suficiente para poder dar servicios informáticos de calidad, servicios más especializados requerirán un conocimiento más profundo de las herramientas y tecnologías específicas.
    - Tener como regla básica seguir al pie de la letra el protocolo SAPITS (original o modificado) para garantizar los derechos humanos y esenciales de los clientes.

2. **Atención**: El establecimiento debe estar preparado para atender al usuario de manera eficiente y efectiva, garantizando la privacidad y seguridad de sus datos en todo momento.

###### Trabajando...

### Fase Intermedia

###### Trabajando...


##### Llamado a la Comunidad
Invitamos a expertos en seguridad, criptógrafos y entusiastas de la privacidad a contribuir con sus conocimientos y experiencia.

## 🔄 Mejora Continua

Agradecemos sugerencias para mejorar la metodología SAPITS manteniendo nuestros principios fundamentales. Por favor, envía tus sugerencias a través de nuestros canales seguros.

---
*Ver la última versión en el historial de commits*

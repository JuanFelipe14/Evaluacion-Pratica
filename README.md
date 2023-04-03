<h1 align="center">Evaluación práctica</h1>

<p align="center">
  <img src="https://media.licdn.com/dms/image/C4E03AQEMRYnUiklfxA/profile-displayphoto-shrink_800_800/0/1662823291516?e=1686182400&v=beta&t=m49NsZ-8APwcVMj67pHrusn7r4IwbzuvHThhFKxfPRY" alt="Juan Felipe Arias" width="80" height="80">
</p>

<p align="center">
  <a href="#ejercicio-1" style="color:red">Ejercicio 1</a> •
  <a href="#ejercicio-2" style="color:orange">Ejercicio 2</a> •
  <a href="#ejercicio-3" style="color:yellow">Ejercicio 3</a> •
  <a href="#ejercicio-4" style="color:green">Ejercicio 4</a> •
  <a href="#ejercicio-5" style="color:blue">Ejercicio 5</a> •
  <a href="#ejercicio-6" style="color:indigo">Ejercicio 6</a> •
  <a href="#ejercicio-7" style="color:violet">Ejercicio 7</a>
</p>

## Ejercicio 1

En este ejercicio se debía demostrar las habilidades de uso de las herramientas **Visual Studio Code** y **Git**. El presente documento es resultado de conocimiento sobre las herramientas **Git y Git Bash**, y los archivos APEX de **Visual Studio Code**.

## Ejercicio 2

A continuación, responderé unas preguntas acerca del protocolo HTTP.

<ul>
  <li><em><b>¿Qué es un servidor HTTP?</b></em></li>
    <ul>
      <li>Un servidor HTTP es un tipo de software que <b>recibe, procesa y responde</b> a las solicitudes de los clientes en la web. Es el responsable de recibir y procesar las solicitudes de los clientes, enviar respuestas y administrar la comunicación entre los diferentes componentes de una aplicación web.</li>
    </ul>
</ul>

<ul>
  <li><em><b>¿Qué son los verbos HTTP? Mencionar los más conocidos</b></em></li>
    <ul>
      <li>Los verbos HTTP se utilizan para solicitar y recibir información en la web. Los verbos se encargan de definir la acción que se desea realizar en un recurso que fue identificado por una URL. Los verbos HTTP que son más conocidos son:</li>
        <ul>
          <li>GET</li>
          <li>POST</li>
          <li>PUT</li>
          <li>DELETE</li>
          <li>HEAD</li>
          <li>PATCH</li>
        </ul>
    </ul>
</ul>

<ul>
  <li><em><b>¿Qué es un request y un response en una comunicación HTTP? ¿Qué son los headers?</b></em></li>
    <ul>
      <li><em>Request</em></li>
        <ul>
          <li>Es una solicitud de un recurso que fue enviado desde un cliente hacia un servidor HTTP.</li>
        </ul>
          <li><em>Response</em></li>
          <ul>
            <li>Es la respuesta al request desde el servidor HTTP, está respuesta suele contener un el recurso que fue solicitado con información adicional como el codigo de estado HTTP y headers.</li>
          </ul>
        <li><em>Headers</em></li>
          <ul>
            <li>Son componentes que brindan información adicional sobre la solicitud o respuesta que se está enviando. Los Headers principalmente sirven para transmitir información sobre el contenido, la longitud, el lenguaje , la autenticación, entre otros componentes.</li>
          </ul>
    </ul>
</ul>

<ul>
  <li><em><b>¿Qué es un queryString? (En el contexto de una url) </b></em></li>
    <ul>
      <li>Es una cadena de caracteres que se utiliza para enviar información hacia el servidor por medio de una solicitud GET HTTP. Este se incluye al final de una URL después del signo "?".
 
</li>
    </ul>
</ul>

<ul>
  <li><em><b>¿Qué es el responseCode? ¿Qué significado tiene los posibles valores devueltos? </b></em></li>
    <ul>
      <li>Es un código numérico de 3 dígitos que indica el estado de la solicitud del cliente al servidor HTTP. El responseCode se agrupa en 5 clases que tienen un significado especifico.</li>
         <ul>
            <li><em>Respuestas informativas (100 - 199)</em> : La solicitud del cliente fue recibida y está siendo procesada.</li>
            <li><em>Respuestas satisfactorias (200 - 299)</em> : La solicitud del cliente ha sido procesada y se ha enviado el resultado solicitado.</li>
            <li><em>Redirecciones (300 - 399)</em> : La solicitud del cliente no se ha completado y que se requiere una acción adicional para completar la solicitud.</li>
            <li><em>Errores del cliente (400 - 499)</em> : La solicitud del cliente no se pudo completar debido a un error en el servidor.</li>
         </ul>
    </ul>
</ul>

<ul>
  <li><em><b>¿Cómo se envía la data en un Get y cómo en un POST?</b></em></li>
    <ul>
      <li><em>GET</em></li>
        <ul>
          <li>Cuando hacemos una solicitud GET, los datos se envían por medio de la URL ya que los parámetros se añaden al final de la URL después del signo "?"  y se delimitan por el símbolo "&". Después, el servidor recibe la solicitud y procesa los parámetros de la URL y genera un response con la respuesta de la solicitud correspondiente.</li>
    </ul>
</ul>
    <ul>
      <li><em>POST</em></li>
        <ul>
          <li>Cuando hacemos una solicitud POST, los datos se envían en el cuerpo de la solicitud, la estructura del cuerpo de POST depende el tipo de datos que se están enviando (Por ejemplo: JSON, XML, etc...) y el servidor procesa los datos recibidos en el cuerpo de la solicitud y genera el response y lo envía. </li>
        </ul>
    </ul>
</ul>

<ul>
  <li><em><b>¿Qué verbo HTTP utiliza el navegador cuando accedemos a una página? </b></em></li>
    <ul>
      <li>Si deseamos acceder a una página web el verbo HTTP que se debe utilizar es GET. Así como mencione anteriormente, el verbo GET se utiliza para solicitar un recurso especifico hacia el servidor web. </li>
    </ul>
</ul>

<ul>
  <li><em><b>Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de estructuras posibles.</b></em></li>
    <ul>
      <li><em>JSON</em></li>
        <ul>
          <li>
            Es un formato de intercambio de datos que es liviano y fácil de usar y comprender por la sintaxis que se utiliza. Es ampliamente utilizado en aplicaciones web y móviles por su legibilidad y compatibilidad con una amplia red de lenguajes de programación.
            <pre>
                {
                  "Nombre": "Juan Felipe",
                  "Edad": 21,
                  "Pais": "Colombia",
                  "Ciudad": "Bogotá D.C.",
                  "Telefonos": [
                    "+57 3195589632",
                    "3195589632"
                  ]
                }
                </pre>
          </li>
        </ul>
        <li><em>XML</em></li>
          <ul>
            <li>
              Es un formato de intercambio de datos basado en etiquetas y atributos. Es un formato un poco más pesado a diferencia de JSON, sin embargo, se utiliza ampliamente en aplicaciones empresariales debido a su capacidad para describir estructuras de datos complejas.
              <pre><code>
&lt;usuario&gt;
    &lt;nombre&gt;Juan Felipe&lt;/nombre&gt;
    &lt;edad&gt;21&lt;/edad&gt;
    &lt;ciudad&gt;Bogotá D.C.&lt;/ciudad&gt;
    &lt;telefonos&gt;
      &lt;telefono&gt;+57 3195589632&lt;/telefono&gt;
      &lt;telefono&gt;3195589632&lt;/telefono&gt;
   &lt;/telefonos&gt;
&lt;/usuario&gt;
            </code></pre>
            </li>
          </ul>
    </ul>
</ul>

<ul>
  <li><em><b>Explicar brevemente el estándar SOAP</b></em></li>
    <ul>
      <li>Es un estandar para la comunicación entre aplicaciones y servios web que utiliza XML para reprensentar los datos y HTTP o HTTPS. SOAP se utiliza en aplicaciones empresariales y en la industria donde se requiere una comunicación confiable y segura entre sistemas distribuidos.</li>
    </ul>
</ul>

<ul>
  <li><em><b>Explicar brevemente el estándar REST Full</b></em></li>
    <ul>
      <li>REST Full es una forma de diseñar servicios web de acuerdo con los principios de REST, que se basa en recursos, URIs y verbos HTTP estándar.  Es ampliamente utilizado en aplicaciones web y es una alternativa popular a SOAP.</li>
    </ul>
</ul>

<ul>
  <li><em><b>¿Qué son los headers en un request? ¿Para qué se utiliza el key Content-type en un header?</b></em></li>
    <ul>
      <li>Los headers en un request proporciona información sobre la solicitud tales como el tipo de contenido, la codificación, la autentificación, entre otros.</li>
      <li><em><b>Content-type</b></em> : Se utiliza para informar al servidor y al cliente sobre el tipo de datos que se están transmitiendo. El valor tiende a ser una cadena de texto que informa acerca del formato de los daos, texto, imagen, etc.</li>
    </ul>
</ul>


## Ejercicio 3

<ul>
  <li><em><b>Realizar un request GET a la URL: https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json</b></em></li>
    <ul>
      <p align="center">
        <img src="https://github.com/JuanFelipe14/Evaluacion-Pratica/blob/main/Imagen1.png" alt="Ejemplo del Ejercicio 3" width="500">
      </p>
      <p align="center">
  <em>Ilustracion 1. Resultado request GET.</em>
</p>
    </ul>
  <li><em><b>Realizar nuevamente un request GET a la URL<b></em></li>
    <ul>
      <p align="center">
        <img src="https://github.com/JuanFelipe14/Evaluacion-Pratica/blob/main/Imagen2.png" alt="Ejemplo del Ejercicio 3" width="500">
      </p>
      <p align="center">
  <em>Ilustracion 2. Registro en archivo JSON.</em>
</p>
    </ul>
    <li><em><b>¿Qué diferencias se observan entre las llamadas el punto 1 y 3?</b></em></li>
      <ul>
        <li><em>Punto 1</em></li>
          <ul>
              <li>Inicialmente, al realizar la solicitud GET se realizar una solicitud a los recursos del link proporcionado y nos desplego el archivo JSON. Después, realizamos una solicitud POST en la que enviamos la información en los datos en el cuerpo de la solicitud y se almaceno la información en el archivo JSON.</li>
          </ul>
        <li><em>Punto 3</em></li>
          <ul>
            <li>La diferencia del punto 1 es que solamente realizamos una solicitud GET para que se nos despliegue la información de la URL proporcionada.</li>
          </ul>
      </ul>
</ul>


## Ejercicio 4

**Mi cuenta en TrailHead**.

***Perfil público***: https://trailblazer.me/id/juanfelipe02

## Ejercicio 5

**Definición datos**

<ol>
  <li><em><b>Lead</b></em></li>
    <ul>
      <li>Un Lead es un cliente potencial o una empresa que ha mostrado algún interés en los productos o servicios que ofrece la empresa. Los Leads almacenan información sobre el cliente potencial, como el nombre, la dirección de correo electrónico, el número de teléfono y la empresa a la que pertenece.</li>
    </ul>
      <li><em><b>Account</b></em></li>
    <ul>
      <li>Un Account es una empresa o una organización con la que la empresa tiene una relación comercial. Las cuentas almacenan información sobre la empresa, como el nombre, la dirección y el número de teléfono</li>
    </ul>
      <li><em><b>Contact</b></em></li>
    <ul>
      <li>Un Contact es una persona con la que la empresa tiene una relación comercial. Los contactos están vinculados a una cuenta y almacenan información sobre la persona, como el nombre, la dirección de correo electrónico y el número de teléfono.</li>
    </ul>
      <li><em><b>Opportunity</b></em></li>
    <ul>
      <li>Un Opportunity es una oportunidad de negocio que se presenta cuando un cliente potencial muestra interés en los productos o servicios de la empresa. Las oportunidades almacenan información sobre la venta, como el monto de la venta, la fecha de cierre y la etapa de la venta.</li>
    </ul>
      <li><em><b>Product</b></em></li>
    <ul>
      <li>Un Product es un producto o servicio que la empresa ofrece. Los productos almacenan información sobre el producto, como el nombre, la descripción y el precio.</li>
    </ul>
      <li><em><b>PriceBook</b></em></li>
    <ul>
      <li>Un PriceBook es una lista de precios para los productos y servicios que ofrece la empresa. Los PriceBooks almacenan información sobre los precios de los productos y servicios</li>
    </ul>
      <li><em><b>Quote</b></em></li>
    <ul>
      <li>Una Quote es una cotización que se le presenta al cliente potencial en relación con una oportunidad de negocio. Las cotizaciones almacenan información sobre los precios y los productos que se ofrecen en la cotización.</li>
    </ul>
      <li><em><b>Asset</b></em></li>
    <ul>
      <li>Un Asset es un activo que se le asigna a una cuenta. Los activos almacenan información sobre el activo, como el nombre, la descripción y el valor.</li>
    </ul>
      <li><em><b>Case</b></em></li>
    <ul>
      <li>Un Case es un problema o una solicitud que se presenta por un cliente. Los casos almacenan información sobre el problema o solicitud, como el nombre del cliente, el problema o solicitud y la fecha de creación.</li>
    </ul>
      <li><em><b>Article</b></em></li>
    <ul>
      <li>Un Article es un artículo de conocimiento que se crea para proporcionar información a los clientes. Los artículos almacenan información sobre el artículo, como el título, el contenido y la fecha de creación.</li>
    </ul>
</ol>

Estos objetos están relacionados entre sí en Trailhead. Por ejemplo, un **Lead** puede convertirse en un **Opportunity**, y un **Opportunity** puede convertirse en un **Quote**. Además, los **Contacts** y las **Accounts** están relacionados, y los casos están relacionados con las **Accounts** y los **Contacts**. La relación entre los objetos permite una gestión eficaz del negocio, desde la captación de nuevos clientes potenciales hasta la resolución de problemas y la generación de ingresos.

<p align="center">
  Diagrama de clases
</p>

<p align="center">
  <img src="https://github.com/JuanFelipe14/Evaluacion-Pratica/blob/main/Diagrama%20de%20clases%20-%20Objetos.jpg" alt="Imagen">
</p>

<p align="center">
  <em>Ilustracion 3. Diagrama de clases de objetos en TrailHead.</em>
</p>

Puedes agregar más detalles sobre el Ejercicio 5 aquí.

## Ejercicio 6

<ul>
  <li><em><b>Soluciones de Saleforce</b></em></li>
    <ul>
      <li>¿Qué es Salesforce?</li>
        <ul>
          <li>Es una empresa líder en el mercado de software empresaria que ofrece una amplia gama de soluciones en la nube para la gestión de relaciones con los clientes, automatización de ventas, marketing digital, atención al cliente, análisis de datos y colaboración empresarial.</li>
        </ul>
      <li>¿Qué es Sale Cloud?</li>
        <ul>
          <li>Es una solución de software empresarial que se enfoca en la gestión de ventas y el seguimiento de clientes y prospectos. Ofrece una variedad de funciones y herramientas para ayudar a los equipos de ventas a optimizar su productividad y eficiencia.</li>
        </ul>
      <li>¿Qué es Service Cloud?</li>
        <ul>
          <li>Es una solución de software empresarial que se enfoca en la gestión de servicio al cliente y soporte técnico. Esta herramienta ayuda a las empresas a proporcionar un servicio al cliente eficiente y personalizado a través de múltiples canales de comunicación.</li>
        </ul>
      <li>¿Qué es Health Cloud?</li>
        <ul>
          <li>Es una solución de software empresarial que se enfoca en la gestión de la atención medica y el seguimiento de pacientes. Es una herramienta que ayuda a las organizaciones de atención médica como hospitales, clínicas y compañías de seguridad de salud, a administrar y coordinar el cuidado de los pacientes de manera más eficiente.</li>
        </ul>
      <li>¿Que es Marketing Cloud?</li>
        <ul>
          <li>Es una solución de software empresarial que se enfoca en la gestión del marketing y la automatización de la comunicación con los clientes. Es una herramienta que ayuda a las empresas a crear y ejecutar campañas de marketing personalizadas y automatizadas a través de diferentes canales de comunicación.</li>
        </ul>
    </ul>
    <li>Funcionalidades de Salesforce</li>
      <ul>
        <li>¿Qué es un RecordType?</li>
          <ul>
            <li>Es un tipo de registro que permite a los usuario personalizar y categorizar los registros en función de atributos específicos y establecer flujos de trabajo, diseño de página y permisos únicos para cada tipo de registro.</li>
          </ul>
        <li>¿Qué es un ReportType?</li>
          <ul>
            <li>Es un tipo de informe o plantillas predefinidas que permiten a los usuarios crear informes basados en la relación entre objetos dentro de Salesforce. </li>
          </ul>
        <li>¿Qué es un Page Layout?</li>
          <ul>
            <li>Es un diseño de página que permite organizar los campos, secciones y objetos en una página de registro.</li>
          </ul>
        <li>¿Qué es un Compact Layout?</li>
          <ul>
            <li>Es una forma de mostrar información relevante de un registro en un espacio limitado, como en la lista de registro o en el feed de noticias de Salesforce.</li>
          </ul>
        <li>¿Qué es un Perfil?</li>
          <ul>
            <li>Es un conjunto de permisos y configuraciones que determinan qué puede hacer un usuario en la plataforma. Estos, definen el acceso, los permisos, la visualicen, las acciones y las configuraciones para los usuarios.</li>
          </ul>
        <li>¿Qué es un Rol?</li>
          <ul>
            <li>Es un objeto de seguridad que se utiliza para controlar el acceso a registros y funcionalidades en Salesforce.</li>
          </ul>
        <li>¿Qué es un Validation Rule?</li>
          <ul>
            <li>Es una regla personalizada que se utiliza para garantizar que los datos ingresados por los usuarios cumplan con ciertas condiciones antes de que se puedan guardar en la base de datos.</li>
          </ul>
        <li>¿Qué diferencia hay entre una relación <em>Master-Detail y Lookup</em>?</li>
          <ul>
            <table>
              <tr>
                <th>Características</th>
                <th>Master-Detail</th>
                <th>Lookup</th>
              </tr>
              <tr>
                <td>Control eliminación</td>
                <td>Es una relación jerárquica en la que el objeto maestro controla la eliminación de registros relacionados.</td>
                <td>No tiene este control y los registros relacionados no se eliminan automáticamente.</td>
              </tr>
              <tr>
                <td>Propagación de valores</td>
                <td>Propaga los valores de los campos del objeto maestro a los registros relacionados.</td>
                <td>No tiene la misma capacidad y los valores deben actualizarse manualmente.</td>
              </tr>
              <tr>
                <td>Acceso a los registros</td>
                <td>No pueden existir sin un registro maestro correspondiente.</td>
                <td>Los registros relacionados pueden existir sin un registro principal correspondiente.</td>
              </tr>
            </table>
          </ul>
        <li>¿Qué es un Sandbox?</li>
          <ul>
            <li>Es un entorno aislado y separado de la producción que permiten a los desarrolladores y equipos de pruebas trabajar de manera segura y eficiente en nuestras funcionalidades y personalizaciones sin afectar la estabilidad de la instancia de producción.</li>
          </ul>
        <li>¿Qué es un ChangeSet?</li>
          <ul>
            <li>Es un conjunto de cambios que se han realizado en una organización y que se desean mover a otra. Es una herramienta que permite a los desarrolladores y administradores reunir y agrupar las modificaciones de configuración y código en una colección.</li>
          </ul>
        <li>¿Para qué sirve el <em>import Wizard</em> en Salesforce?</li>
          <ul>
            <li>Es una herramienta muy útil para importar grandes cantidades de datos de forma rápida y sencilla. Es ideal para los usuarios que necesitan importar datos de forma masiva desde diversas fuentes y no tienen conocimientos técnicos avanzados.</li>
          </ul>
        <li>¿Para qué sorve la funcionalidad <em>Web to lead?</em></li>
          <ul>
            <li>Es una herramienta que permite a las empresas capturar clientes potenciales directamente desde su sitio web y automatizar el proceso de ingreso de datos.</li>
          </ul>
        <li>¿Para qué sirve la funcionalidad Web to Case?</li>
          <ul>
            <li>Es una herramienta que permite a las empresas capturar casos directamente desde su sitio web y automatizar el proceso de ingreso de casos en Salesforce.</li>
          </ul>
        <li>¿Para qué sirve la funcionalidad Omnichannel?</li>
          <ul>
            <li>Permite que las empresas proporcionen una experiencia de servicio al cliente consistente y personalizada a través de múltiples canales de comunicación en una sola plataforma unificada.</li>
          </ul>
        <li>¿Para qué sirve la funcionalidad Chatter?</li>
          <ul>
            <li>Es una herramienta de colaboración social que mejora la comunicación y la colaboración en tiempo real dentro de Salesforce. Esto permite que los usuarios compartan información o colaborar con otro usuario online.</li>
          </ul>
      </ul>
      <li>Conceptos generales</li>
        <ul>
          <li>¿Qué significa SaaS</li>
            <ul>
              <li>Es un modelo de distribución de software en el que el proveedor de software aloja la aplicación en la nube y la entrega a los usuarios a través de internet. En vez de comprar una licencia de software y descargarlo en su computadora, los usuarios de SaaS acceden a la aplicación a través de un navegador web y pagan por el uso del software a través de una suscripción mensual o anual.</li>
            </ul>
          <li>¿Salesforce es SaaS</li>
            <ul>
              <li>Si, porque Salesforce es una plataforma que se aloja en la nube y se entrega a los usuarios de internet. Salesforce permite a los usuarios acceder a sus datos y aplicaciones desde cualquier lugar y momento para aumentar la flexibilidad y eficiencia de la empresa.</li>
            </ul>
          <li>¿Qué significa que una solución sea Cloud?</li>
            <ul>
              <li>Significa que se aloja en la nube y se entrega a los usuarios por medio de internet en ves de instalar un software en su propia estructura de TI.</li>
            </ul>
          <li>¿Qué significa que una solución sea On-Premise?</li>
            <ul>
              <li>Significa que se ejecuta en los servidores de la propia organización en lugar de alojarse en la nube y entregarse por medio de internet.</li>
            </ul>
          <li>¿Qué es un pipeline de ventas?</li>
            <ul>
              <li>Es un modelo visual que representa el proceso de ventas de una empresa, desde la captación de clientes potenciales hasta la conversión de esos clientes potenciales en clientes pagadores.</li>
            </ul>
          <li>¿Qué es un funnel de ventas?</li>
            <ul>
              <li>Es un modelo conceptual que representa el proceso de ventas de una empresa de una manera más detallada que el pipeline de ventas. El objetivo es mostrar cómo los clientes potenciales se convierten en clientes pagadores a medida que avanzan por diferentes etapas del proceso de ventas.</li>
            </ul>
          <li>¿Qué significa Customer Experience?</li>
            <ul>
              <li>Significa a la percepción global que tiene un cliente de la interacción con una empresa en todas sus etapas, desde el cubrimiento del producto o servicio pasando por la compra y la interacción postventa.</li>
            </ul>
          <li>¿Qué significa que un negocio sea B2B?¿Qué significa que un negocio sea B2C?¿Qué es un KPI?</li>
            <ul>
              <li><em>B2B</em></li>
                <ul>
                  <li>Un negocio B2B se refiere a la relación comercial entre dos empresas. Una empresa vende productos o servicios a otra empresa.</li>
                </ul>
              <li><em>B2C</em></li>
                <ul>
                  <li>Un negocio B2C se refiere a la relación comercial entre una empresa y un consumidor final. Una empresa vende productos o servicios directamente a consumidores.</li>
                </ul>
              <li><em>KPI</em></li>
                <ul>
                  <li>Es un indicador clave de rendimiento que se utiliza para medir el desempeño de un negocio o de un proceso especifico.</li>
                </ul>
            </ul>
          <li>¿Qué es una API y en qué se diferencia de una Rest API?</li>
            <ul>
              <li><em>API</em></li>
                <ul>
                  <li>De sus siglas “Application Programming Interface”, se refiere a un conjunto de reglas, protocolos y herramientas que permiten que diferentes aplicaciones se comuniquen entre sí.</li>
                </ul>
              <li><em>API REST</em></li>
                <ul>
                  <li>Es un tipo de API web que se comunica a través del protocolo HTTP.</li>
                </ul>
              <li><em>Diferencias</em></li>
                <ul>
                  <li>API es un conjunto de reglas y protocolos que permite la comunicación entre diferentes aplicaciones, mientras que una API REST es un tipo especifico de API web que utiliza el protocolo HTTP y el formato JSON para la comunicación.</li>
                </ul>
            </ul>
          <li>¿Qué es un Proceso Batch?</li>
            <ul>
              <li>Es un tipo de proceso automatizado que se ejecuta en segundo plano y realiza tareas en lotes. Se utiliza para realizar acciones en un gran número de registros de manera programada en lugar de realizar cada tarea individualmente.</li>
            </ul>
          <li>¿Qué es Kanban?</li>
            <ul>
              <li>Es un método de gestión de procesos y proyectos que se centran en la visualización del flujo de trabajo y en la gestión del trabajo en curso. Las tareas se visualizan en un tablero con diferentes columnas que representan los diferentes estados del proceso.</li>
            </ul>
          <li>¿Qué es un ERP?</li>
            <ul>
              <li>Proveniente de las siglas “Enterprise Resource Planning”, es un sistema integrado de software que permite a las empresas gestionar y coordinar sus procesos y recursos empresariales, incluyendo finanzas, recursos humanos, ventas y marketing, entre otros.</li>
            </ul>
          <li>¿Salesforce es un ERP?</li>
            <ul>
              <li>A pesar de ser un software de gestión empresarial, no se considera un ERP. Sin embargo, Salesforce es un sistema de gestión empresarial muy completo y se puede integrar con otros sistemas ERP y aplicaciones empresariales para mejorar la eficiencia y la coordinación entre los departamentos y funcionales empresariales.</li>
            </ul>
        </ul>
</ul>

## Ejercicio 7

Este ejercicio se encuentra dentro de los archivos del repositorio, son los archivos llamados **EmailTrigger** y **EmailHandler**. El objetivo del ejercicio 7 era desarrollar un trigger para que cuando un usuario modifique o cree un contacto de Salesforce se invoque al Web Service con el id (consultado haciendo un GET con POSTMAN en el link que dejare más abajo), y finalmente obtener los datos de email de la respuesta y actualizar el campo email del contacto.

Link: https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json

<p align="center">
  <img src="https://user-images.githubusercontent.com/20113120/229582837-044aedb4-6042-4064-9901-8cad3a900faa.png" alt="Ejemplo del Ejercicio 7" width="500">
</p>

<p align="center">
  <em>Ilustración 4. Resultado ejercicio 7.</em>
</p>

<br></br>
<br></br>
<br></br>

<ul>
  <li><em><b>Referencias bibliográficas</b></em></li>
    <ol>
      <li>Generalidades del protocolo HTTP - HTTP | MDN. (2022, 26 noviembre). https://developer.mozilla.org/es/docs/Web/HTTP/Overview</li>
      <li>query-string. (2022, diciembre). npm. https://www.npmjs.com/package/query-string</li>
      <li>JSON vs XML. (s. f.). https://www.w3schools.com/js/js_json_xml.asp</li>
      <li>SOAP (Simple Object Access Protocol). (2004, 7 julio). Desarrollo Web. https://desarrolloweb.com/articulos/1557.php</li>
      <li>REST FULL. (s. f.). Bing. https://www.bing.com/search?q=REST+FULL</li>
      <li>Content-Type - HTTP | MDN. (2023, 3 marzo). https://developer.mozilla.org/en-US/docs/web/http/headers/content-type</li>
      <li>Apex & .NET Basics. (s. f.). Salesforce Trailhead. https://trailhead.salesforce.com/content/learn/modules/apex_basics_dotnet?trailmix_creator_id=strailhead</li>
      <li>Modelado de datos. (s. f.). Salesforce Trailhead. https://trailhead.salesforce.com/es/content/learn/modules/data_modeling</li>
      <li>Fundamentos y base de datos de Apex. (s. f.). Salesforce Trailhead. https://trailhead.salesforce.com/es/content/learn/modules/apex_database</li>
      <li>Desencadenadores de Apex. (s. f.). Salesforce Trailhead. https://trailhead.salesforce.com/es/content/learn/modules/apex_triggers</li>
      <li>Servicios de integraciÃ3n de Apex. (s. f.). Salesforce Trailhead. https://trailhead.salesforce.com/es/content/learn/modules/apex_integration_services</li>
      <li>Sales Cloud Overview. (s. f.). Salesforce. https://www.salesforce.com/mx/form/sem/sales-cloud/?d=7013y000002Z9bDAAS</li>
      <li>Solutions. (s. f.). Salesforce. https://www.salesforce.com/products/platform/solutions/</li>
      <li>Help And Training Community. (s. f.-b). https://help.salesforce.com/s/articleView?language=en_US&id=sf.creating_record_types.html</li>
      <li>W. (2022b, marzo 9). Different Types of Reports in Salesforce. Alternative Solutions Consulting. https://alt-solut.com/blog-post/different-types-of-reports-in-salesforce/</li>
      <li>Team, A. (2022, 18 julio). Layouts in Salesforce - All You Need To Know. APPSeCONNECT. https://www.appseconnect.com/layouts-in-salesforce/</li>
      <li>Web-to-Lead: Converting Online Prospects to Sales Leads in. (s. f.). Salesforce. https://www.salesforce.com/products/guide/lead-gen/web-to-lead/</li>
      <li>DeveloperForce. (s. f.). Salesforce Developers Forums. https://developer.salesforce.com/forums/?id=9060G000000I51XQAS</li>
      <li>Help And Training Community. (s. f.-c). https://help.salesforce.com/s/articleView?language=en_US&id=omnichannel_intro.htm</li>
      <li>Chatter - Red social empresarial y solución de software colaborativo. (s. f.). Salesforce. https://www.salesforce.com/es/products/chatter/overview/</li>
      <li>¿Qué es SaaS? Software como servicio | Microsoft Azure. (s. f.). https://azure.microsoft.com/es-es/resources/cloud-computing-dictionary/what-is-saas/</li>
      <li>Carrero, L. (2023, 23 marzo). Cloud computing: la guía definitiva (2023). Stackscale. https://www.stackscale.com/es/blog/cloud-computing-guia-definitiva/</li>
      <li>On-premises: el modelo de software basado en el servidor. (2020, 20 octubre). IONOS Digital Guide. https://www.ionos.es/digitalguide/servidores/know-how/que-es-on-premises/</li>
      <li>Santamaría, M. (2023, 7 febrero). Pipeline de ventas: Qué es, para qué sirve, cómo hacerlo. Forcemanager. https://www.forcemanager.com/es/blog/pipeline-de-ventas/Customer</li>
      <li>D. (2022a, julio 18). ¿Qué es el Customer Experience? Asociación DEC. https://asociaciondec.org/blog-dec/que-es-el-customer-experience/38130/</li>
      <li>Nirian, P. O. (2022, 24 noviembre). Omnicanalidad. Economipedia. https://economipedia.com/definiciones/omnicanalidad.html</li>
      <li>Da Silva, D. (2021, 6 abril). ¿Qué es B2B y B2C? ¿Cuáles son sus principales características? Zendesk MX. https://www.zendesk.com.mx/blog/b2b-b2c-que-es/</li>
      <li>A. (s. f.). Qué es un KPI, para qué sirve y cómo utilizarlo en tu proyecto •. Asana. https://asana.com/es/resources/key-performance-indicator-kpi</li>
      <li>S. (2019, 25 enero). Diferencias entre un proceso en continuo y un proceso batch. SACOME. https://www.sacome.com/diferencias-proceso-continuo-proceso-batch/</li>
      <li>A. (s. f.-a). ¿Qué es la metodología Kanban y cómo funciona? •. Asana. https://asana.com/es/resources/what-is-kanban</li>
      <li>¿Qué es ERP? | Definición de planificación de recursos empresariales | SAP Insights. (s. f.). SAP. https://www.sap.com/latinamerica/insights/what-is-erp.html</li>
    </ol>
</ul>

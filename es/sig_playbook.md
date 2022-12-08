# Libro de jugadas SI 003

## Alcance de un SIG 001

TensorFlow alberga *grupos de interés especial* (SIG) para centrar la colaboración en áreas particulares. Los SIG hacen su trabajo en público. Para unirse y contribuir, revisar el trabajo del grupo y ponerse en contacto con el líder SIG. Las políticas de membresía varían según el SIG. d

El alcance ideal para un SIG cumple con un dominio bien definido, donde la mayoría de la participación es de la comunidad. Además, debe haber suficiente evidencia de que hay miembros de la comunidad dispuestos a participar y contribuir en caso de que se establezca el grupo de interés.

No todos los SIG tendrán el mismo nivel de energía, amplitud de alcance o modelos de gobierno, así que espere cierta variabilidad.

Consulta la lista completa de [SIG de TensorFlow](https://github.com/tensorflow/community/tree/master/sigs) .

### 002 Sin objetivos: lo que *no* es un SIG

Los SIG están destinados a facilitar la colaboración en el trabajo compartido. Un SIG es por lo tanto:

- *No es un foro de soporte* : una lista de correo y un SIG no es lo mismo. sa
- *No se requiere de inmediato* : al principio de la vida de un proyecto, es posible que no sepa si ha compartido trabajo o colaboradores.
- *Mano de obra no gratuita* : se requiere energía para crecer y coordinar el trabajo de forma colaborativa.

Nuestro enfoque para la creación de SIG será conservador: gracias a la facilidad de iniciar proyectos en GitHub, hay muchas vías en las que se puede colaborar sin necesidad de un SIG.

## SIG ciclo de vida 004 ss

### Investigación y consulta 005

Los proponentes de grupos deben reunir pruebas para su aprobación, como se especifica a continuación. Algunas vías posibles a considerar son:

- Un problema bien definido o un conjunto de problemas que el grupo resolvería.
- Consulta con los miembros de la comunidad que se beneficiarían, evaluando tanto el beneficio como su disposición a comprometerse.
- Para proyectos existentes, evidencia de problemas y relaciones públicas de que los colaboradores se preocupan por el tema.
- Metas potenciales a alcanzar por el grupo.
- Requerimientos de recursos para operar el grupo.

Incluso si la necesidad de un SIG parece evidente, la investigación y la consulta siguen siendo importantes para el éxito del grupo.

### Creando el nuevo grupo

El nuevo grupo debe seguir el siguiente proceso para la constitución. En particular, debe demostrar:

- Un propósito claro y un beneficio para TensorFlow (ya sea en torno a un subproyecto o área de aplicación)
- Dos o más colaboradores dispuestos a actuar como líderes del grupo, existencia de otros colaboradores y evidencia de demanda para el grupo
- Recursos que requerirá inicialmente (generalmente, una lista de correo y una llamada regular de VC).

La aprobación para el grupo será otorgada por una decisión del Equipo de la comunidad de TF, definido como los mantenedores del proyecto tensorflow/community. El equipo consultará a otras partes interesadas según sea necesario.

Antes de ingresar a las partes formales del proceso, se recomienda consultar con el equipo de la comunidad de TensorFlow, community-team@tensorflow.org. Es muy probable que se requiera conversación e iteración antes de que la solicitud SIG esté lista.

La solicitud formal para el nuevo grupo se realiza enviando una carta como RP a tensorflow/community e incluyendo la solicitud en los comentarios sobre el RP (consulte la plantilla a continuación). Tras la aprobación, el RP del grupo se fusionará y se crearán los recursos necesarios.

### Solicitud de plantilla para nuevo SIG

Esta plantilla estará disponible en el repositorio de la comunidad: [SIG-request-template.md](https://github.com/tensorflow/community/blob/master/governance/SIG-request-template.md) .

### fletamento

Cada grupo se establecerá con un estatuto y se regirá por el código de conducta de TensorFlow. Los archivos del grupo serán públicos. La membresía puede estar abierta a todos sin aprobación o disponible a pedido, pendiente de la aprobación del administrador del grupo.

La carta debe nombrar un administrador. Además de un administrador, el grupo debe incluir al menos una persona como líder (puede ser la misma persona), que servirá como punto de contacto para la coordinación, según se requiera, con el equipo de la comunidad de TensorFlow.

Esta carta se publicará inicialmente en la lista de correo del grupo. El repositorio de la comunidad en la organización TensorFlow GitHub archivará dichos documentos y políticas ( [ejemplo de Kubernetes](https://github.com/kubernetes/community) ). A medida que un grupo desarrolla sus prácticas y convenciones, esperamos que las documente en la parte correspondiente del repositorio de la comunidad.

### Colaboración e inclusión

Si bien no es obligatorio, el grupo debe optar por hacer uso de la colaboración a través de llamadas de conferencia programadas o canales de chat para realizar reuniones. Cualquier reunión de este tipo debe anunciarse en la lista de correo y las notas deben publicarse en la lista de correo después. Las reuniones periódicas ayudan a impulsar la rendición de cuentas y el progreso en un SIG.

Los miembros del equipo de la comunidad de TensorFlow supervisarán de forma proactiva y animarán al grupo a debatir y actuar según corresponda.

### Lanzamiento

Actividades requeridas:

- Notificar a los grupos de discusión general de TensorFlow ( [discutir@](https://groups.google.com/a/tensorflow.org/forum/#!forum/discuss) , [desarrolladores@](https://groups.google.com/a/tensorflow.org/forum/#!forum/developers) ).
- Agregar SIG a las páginas de la comunidad en el sitio web de TensorFlow.

Actividades opcionales:

- Creación de una publicación de blog para la comunidad de blogs de TensorFlow.

### Sanidad y terminación de SIGs

El equipo de la comunidad de TensorFlow hará todo lo posible para garantizar la salud de los SIG. De vez en cuando, solicitará al líder del SIG que proporcione un informe del trabajo del SIG, que se utilizará para informar a la comunidad más amplia de TensorFlow sobre la actividad del grupo.

Si un SIG ya no tiene un propósito útil o una comunidad interesada, puede ser archivado y dejar de funcionar. El equipo de la comunidad de TF se reserva el derecho de archivar dichos SIG inactivos para mantener la salud del proyecto en general, aunque es un resultado menos preferible. Un SIG también puede optar por disolverse si reconoce que ha llegado al final de su vida útil.

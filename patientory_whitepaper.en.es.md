Title:  Patientory: Una red punto a punto para el cuidado de la salud per medio del almacenamiento de Registros Médicos Electrónicos v.1.0
Author: Chrissa McFarlane, Michael Beer, Jesse Brown, Nelso Prendergast
Date:   Abril 2017

**Este documento es para propósitos informativos únicamente y no constituye una
oferta o solicitud para vender acciones o bonos en Patientory o cualquier
compañía relacionada o asociada. Cualquier oferta o solicitud se realizará
únicamente por medio de un documento de oferta confidencial y en acuerdo con los
términos de todas las leyes aplicables a bonos y otras leyes.**

## Abstract ##

Un intercambio de información de salud (HIE) apoyado en una blockchain puede
{==liberar==} el verdadero valor de la interoperabilidad y ciber seguridad. Este
sistema tiene el potencial de eliminar la fricción y los costos de los actuales terceros
intermediario, cuando se considera la gesitón de la salud de la población.
Existen promesas de mejora de integración de los datos, reducción de costos de
transacción, decentralización y desintermediación de confianza. Ser capaz de
coordinar el cuidado de un paciente por medio de una HIE con blockchain
esencialmente disminuye algunos servicios innecesarios y pruebas duplicadas, con
reducción de costos y mejoras en las ineficiencias del ciclo de cuidado contínuo
del paciente, mientras se adhiere a todas las reglas y los estándares HIPAA. Un
protocolo centrado en el paciente soportado en tecnología blockchain, Patientory
está cambiando la forma en la que los participantes del sistema de salud
gestionan datos médicos electrónicos e interactuan con los equipos de cuidado
clínico.


1. Introduction

  1. ¿Qué es Blockchain?
  
  La tecnología detrás de la moneda digital bitcoin, el nacimiento de blockchain
  se remonta a la persona (o grupo) sin identificar, con pseudónimo conocido como
  Satoshi Nakamoto. Desde 2009 blockchain ha ganado un uso más generalizado en la
  industria financiera, con una variedad de negocios y servicios soportados en blockchain que
  están entrando al mercado. La tecnología blockchain se usa para compartir un
  libro de transacciones a través de una red de negocios sin el control por parte
  de una única entidad. El libro distribuído facilita la creación de relaciones
  comerciales de costos eficientes donde virtualmente cualquier cosa de valor
  puede ser seguido y negociado din requerir un punto central de control. La
  tecnología pone la privacidad y el control de los datos en las manos del
  individuo. La confianza e integridad es establecida sin apoyarse en
  intermediarios.

  2. Infraestructura de Salud actual
  
  Realinear el enfoque basado en "procedimientos" hacia un "tratamiento
  holístico del individuo" requiere que los Proveedores de Salud formen "redes"
  que trabajen juntas hacia un objetivo en común de mejorar el resultado de los
  tratamientos de los pacientes bajo su cuidado, en cuidados post-tratamiento o
  entre tratamientos. La necesidad de cooperación entre proveedores de salud,
  pasando desde especialistas, médicos de tratamiento primario, cuidadores y
  proveedores de bienestar (como nutricionistas y enfermeros de rehabilitación)
  resulta en un incremento del uso de tecnologías digitales. Aunque estas
  soluciones han mejorado significativamente el seguimiento y la eficiencia en
  la entrega de los cuidados de salud, también han resultado en crear silos de
  información de salud, principalmente dentro de los sistemas de registros
  médicos electrónicos (EMR).

  Organizaciones gubernamentales y de salud gastan tiempo y dinero significativo
  en la construcción y manejo de sistemas de información tradicionales, así como
  intercambio de datos; requieren recursos para solucionar constantemente
  problemas, actualizar información, ejecutar medidas de respaldo y recuperación
  de información, así como extraer información para reportes.
  Las leyes federales y programas de incentivos han hecho los datos de salud más
  accesibles, en respuesta a la resistencia de los hospitales en el tema de
  implementaciones EMR. Sin embargo, la gran mayoría de sistemas hospitalarios
  no pueden aún compartir su información en forma fácil ni segura. Como
  resultado de esto, los doctores pasan más tiempo escribiendo que hablando con
  sus pacientes. El agotamiento de los médicos pasó de un 45% a un 54% ente 2011
  y 2014[][#Begoyan]

  Aunque existe la noción de información de salud individualizada tanto en el
  aspecto clínico como de bienestar, esta no ha sido bien llevada hacia planes
  de cuidado "personalizados". Más aún, aunque hay una gran cantidad de datos,
  el ecosistema de salud en general es incapaz de crear adecuadamente un valor o
  arriesgarse con big data para ayudar a predecir mejor futuros episodios de un
  paciente.

  Por tanto, las soluciones actuales generadas por la industria de tecnologías
  en salud, ha resultado en una elección difícil entre cuidado y privacidad /
  fraude económico para los pacientes. Vemos este problema en expansión a medida
  que los datos creados por la industria crece. **La tecnología segura de
  blockchain, sus propiedades y su naturaleza distribuida pueden ayudar a
  reducir el costo y la eficiencia de estas operaciones así como proveer una
  infraestructura segura viable**

  3. Relación Paciente - Proveedor

  El nuevo paradigma de salud demanda la necesidad de un cuidado efectivo y
  óptimo de los pacientes para obtener mejores resultados de los tratamientos.
  Esto requiere que los principales proveedores de salud puedan coordinar
  activamente y colaborar con otros proveedores relacionados, así como
  organizaciones conexas, como laboratorios y farmacias. En últimas, para que
  esto funcione, los registros de los pacientes necesitan ser actualizados y
  modificados en una forma ágil.

  El software de EMR actualmente prohibe una efectiva relación
  paciente-proveedor. Los portales para pacientes tienen una interacción mínima
  entre pacientes, como resultado de una experiencia separada. Más aún, este
  software sólo provee una capacidad limitada de intercambio de información de
  un sistema a otro y usualmente requiere un individuo designado que sea capaz
  de realizar esta transferencia de información. Esto ha llevado a un aumento en
  la cantidad de retrasos entre organizaciones durante la entrega de los
  cuidados para el paciente y ha resultado también en la reducción en general de
  la calidad de la entrega de los cuidados. Igualmente, a medida que los
  proveedores gastan más de su tiempo envueltos en coordinación, su efectividad
  en el tratamiento de los pacientes y su carga laboral se ha incrementado
  significativamente resultando en un impacto negativo en los resultados de sus
  pacientes.

  En adición, dado que muchos doctores no quieren que sus pacientes accedan sus
  registros electrónicos de salud (EHR), los pacientes toman una actitud pasiva
  en el seguimiento de su salud. Esto en últimas los hace sentir sin control y
  sin sentido de pertenencia sobre su salud, llevando al paciente a sentirse
  frustrado y desconectarse de su cuidado. Aunque hay un reciente incremento en
  las aplicaciones móviles de salud que ayudan a los individuos a hacer un
  seguimiento de sus signos vitales y parámetros de salud, la novedad no se ha
  aprovechado para mejorar los cuidados del paciente, su adherencia o los
  resultados, ya que también se enfrentan a los retos de estar integrados a los
  EHR.

2. Visión general del sistema

![Estructura de Patientory][fig_estructura_patientory]

Los problemas actuales se resuelven usando la Red Blockchain Patientory. Los
sistemas EMR tradicionales son estructuras centralizadas, sujetas a violaciones
de seguridad, regulaciones estrictas y costos extra muy onerosos. Implementando
la infraestructura Blockchain de Patientory, los proveedores verán una
eliminación de las brechas de seguridad, un canal para facilitar la coordinación
con resultados visibles en la mejora general de la salud de los pacientes. En la
figura se muestra un esquema que describe la infraestructura blockchain de
Patientory y su interoperabilidad entre pacientes y proveedores



[#Begoyan]: Begoyan, A. "An overview of interoperability standards for electronic health records." USA: society for design and process science (2007).

[fig_estructura_patientory]: fig_estructura_patientory.png "Estructura de
Patientory

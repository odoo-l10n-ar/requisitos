# Requisitos

El objetivo de este repositorio es aceptar propuestas de [requisitos](http://es.wikipedia.org/wiki/Requisito_funcional) que no fueron implementados en esta localización. Por favor lea atentamente cómo realizar propuestas para una implementación eficiente.

## ¿Qué requisitos son aceptados?

Los requisitos que aceptamos deben:

* Tener una explicación porqué el requisito es aplicable a más de una empresa Argentina.
* Debe incorporar suficiente documentación clara y concisa para poder implementarse.
 * Si lo que se requiere son reportes, los mismos deben ser incorporados en las propuestas.
 * Si lo que se requiere es una funcionalidad, la misma tiene que estar descripta con ejemplos bien concisos (ver casos de test)
 * Si lo que se requiere es importar o exportar archivos, debe incorporar documentación que describa el formato de los archivos, o en consecuencia suficientes archivos de ejemplos para realizar ingeniería reversa.
 * Si lo que quiere es subir un desarrollo propio, para nosotros eso es suficiente documentación. Por supuesto debe cumplir con los [requisitos de homologación](https://github.com/odoo-l10n-ar/odoo-l10n-ar.github.io/wiki/Homologaci%C3%B3n-de-M%C3%B3dulos) para que sea aceptado. Igual, es bienvenida cualquier información extra. En el caso de que usted haya desarrollado un módulo que resuelve una implementación ya resuelta le recomendamos que haga una exposición clara del porque debería pertenecer a la localización. Le recomendamos en este último caso que lea la [propuesta de organización de la localización](https://github.com/odoo-l10n-ar/odoo-l10n-ar.github.io/wiki/Propuesta-para-organizar-la-localizaci%C3%B3n-argentina)

**Una vez que complete estos items, lo invitamos a subir su propuesta a [Issues](https://github.com/odoo-l10n-ar/requisitos/issues).**

## ¿Cuánto tiempo llevará la implementación de los mismos?

Todo depende los recursos libres existentes, o del recurso monetario que esté disponible para ejecutarlo. Pero siempre respetaremos las siguientes etapas:

* **Evaluación**. Se evaluará si el requisito es implementable con los datos expuestos. Si es así se podrá pasar a la siguiente etapa.
* **Asignación de módulo**. Muchos de los requisitos se hacen funcionales por módulos. Si ya existe un módulo que puede implementar ese requisito, se creará un issue en ese módulo. En caso contrario se creará un nuevo módulo específico para ese requisito.
* **Asignación de desarrolladores**. Se asignará un desarrollador responsable de diseñar e implementar el módulo.
* Diseño del módulo. El módulo será diseñado a partir de la documentación publicada en el issue. Contará con su documentación para que otros desarrolladores puedan participar en el proyecto.
* **Implementación del módulo**. Se aceptará aportes de cualquier desarrollador, y por supuesto se le asignará la autoría y el reconocimiento correspondiente. Deberá cumplir con la estructura que se determina en la [Homologación de los módulos](https://github.com/odoo-l10n-ar/odoo-l10n-ar.github.io/wiki/Homologaci%C3%B3n-de-M%C3%B3dulos)
* **Evaluación del módulo**. El módulo tendrá varias etapas de desarrollo, la primera es Draft, Alpha, Beta y Estable. Para cambiar de una a otra deben cumplirse varios requisitos a detallar:
 * **Draft**. el módulo recién está escribiendose. No es funcional o no tiene ningún test automático implementado.
 * **Alpha**. el módulo es funcional pero hay test automáticos que no se están cumpliendo.
 * **Beta**. el módulo es funcional y se cumplen con todos los test automáticos desarrollados.
 * **Estable**. el módulo es funcional, cumple con todos los test automáticos y fue probado en ambiente de producción.

Pasar cada etapa puede llevar su tiempo, es por ello que es muy importante la documentación. La misma permite encarar los problemas más rápidos y sin reinventar la rueda.

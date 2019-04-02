# Ocultar o mostrar un campo

Para mostrar un campo según una condición podemos seguir la siguiente estrucutura:

~~~xml
<field name="subscriptionDays" attrs="{'invisible':[('type', '!=', 'service')]}"/>
~~~

Aqui le estamos indicando que el campo `subscriptionDays` sólo se motrará visible si el campo `type` es `service`.

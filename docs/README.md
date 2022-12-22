# Olimpica

### Quick order

Este componente permite realizar compras rapidas a través de la informacion generada por el SKU


![](https://github.com/Andrezgrondona/itgloberspartnercl-quick-order/blob/main/react/src/assets/quick-order.png?raw=true)

----------------------
### Configuracion

#### Paso 1- Inicio
Acceda a la guia basica de configuracion de VTEX IO y configure su entorno de trabajo antes de utilizar este componente


#### Paso 2 - Clonar el repositorio
Clona este repositorio en tu maquina local para poder trabajar y accede a el por tu terminal.


#### Paso 3 - Edita el manifest.json
Una vez clonado el repositorio hay que hacer unas cuantas modificaciones en el manifest.json del proyecto.

Tendras que modificar valores de la propiedad vendor por el nombre de la cuenta en la que estes trabajando. la propiedad name no es obligatoria modificarla para su uso pero puedes cambiarla por el nombre que quieras

`"vendor": "name-vendor"`, `"name": "my-test-theme"`

--------

#### Paso 4 -Gestor de paquetes

Se debe ejecutar el comando `yarn install` en la terminal de la carpeta `React` para instalar el gestor de paquetes

#### Paso 5 - Desinstalar el store-theme predeterminado
Al ejecutar vtex list, puede verificar si algún tema está instalado.

Es común tener ya instalado un vtex.store-theme cuando inicia el proceso de desarrollo frontal de la tienda.

Se debera ejecutar el siguiente comando para realizar la desinstalacion
`vtex uninstall vtex.store-theme@0.0.1`

#### Paso 6 - Entorno trabajo

Añade a tu manifest.json, la dependencia  `itgloberspartnercl.quick-order`

Se debe revisar en la version en la cual esta actualmente `"itgloberspartnercl.quick-order": "0.x"`

Para usar el componente agregarlo asi: `"quick-order"`

--------

#### Paso 7 - Dependencias

En el archivo `manifest.json`,  de deben agregar las siguientes dependencias:

	"vtex.checkout-graphql": "0.x",
	"vtex.store-graphql": "2.x"

---------

# EPL styles

Este proyecto tiene la finalidad de implementar un diseño responsive y una variante oscura (dark theme) a la página actual de EPL https://www.epublibre.org

## Diseño responsive

| Mobile (`428px`) | Tablet (`810px`) | Desktop (`940px`) |
|:---|:---|:---|
|<img height="250px" src="https://github.com/user-attachments/assets/0dd674a7-26bf-4f59-98da-b2c9f7d8c91a">|<img height="250px" src="https://github.com/user-attachments/assets/aae5eb98-16c9-4be2-a18c-304b58214b67">|<img height="250px" src="https://github.com/user-attachments/assets/6ccda961-5659-4ddb-a88f-acff4d168d9e">|

## Temas

|Claro|Oscuro|
|:---|:---|
|![image](https://github.com/user-attachments/assets/d57c445a-4e2e-4c02-95bf-341d1c1f7231)|![image](https://github.com/user-attachments/assets/7bdb67e0-9bea-42da-a83b-815b1bf81ff4)|

# Instrucciones

Instrucciones para implentar estos estilos en la web de EPL, en cada página:

1. Agregar `<meta name="viewport" content="width=device-width, initial-scale=1">` en el `head`
2. Agregar el archivo [base.css](src/base.css), ya que contiene estilos comunes a todas las páginas
3. Agregar el archivo correspondiente a cada página

> nota: los archivos CSS usados en este proyecto sobreescriben los estilos actuales de Bootstrap.

## Probar los estilos en vivo

Para probar los estilos antes de implementarlos definitivamente se pueden usar las herramientas del desarrollador para agregar el tag y los estilos correspondientes en cualquier browswer.

Para hacer pruebas rápidas se pueden usar dos extensiones:
- Meta Viewport Adder para agregar automáticamente el meta tag `viewport` (https://addons.mozilla.org/en-US/firefox/addon/meta-viewport-adder/)
- Stylus para agregar por defecto los estilos necesarios, el base y el específico para cada página (https://addons.mozilla.org/en-US/firefox/addon/styl-us/)

# Progreso

La versión Desktop se mantiene sin cambios y se usa solo como referencia. No todas las vistas/páginas requieren de un estilo adicional aparte del estilo base.

| Vista | Página | Mobile (`428px`) | Tablet (`810px`) | Desktop (`940px`) | Desktop dark |
|:---|:---|:---|:---|:---|:---|
|__ACCESO__|[acceso/login](https://www.epublibre.org/acceso/login)|[image](https://github.com/user-attachments/assets/3306c135-b9fc-4a01-a12c-cafd12ca3273)|[image](https://github.com/user-attachments/assets/a8e7cfc1-75be-4d95-b4c5-9b67891af66b)|[image](https://github.com/user-attachments/assets/e4ee8efa-d58d-43ae-a7ed-3d76fa0fa55b)|[image](https://github.com/user-attachments/assets/3343bc32-86e5-47da-812c-79531ded077d)|
||[acceso/solicitar](https://www.epublibre.org/acceso/solicitar)|[image](https://github.com/user-attachments/assets/23fa04d8-c0c9-43b4-ac81-32fc5b917e68)|[image](https://github.com/user-attachments/assets/2e080616-f7f2-4c31-89b6-743d40aae4ea)|[image](https://github.com/user-attachments/assets/3b0950cf-38f8-43cd-a4c3-b85c819f99c5)|[image](https://github.com/user-attachments/assets/b6089aaa-f576-4f3a-b653-0c9c827e979a)|
|__AUTOR__|[autor/index/[id]](https://www.epublibre.org/autor/index/216)|[image](https://github.com/user-attachments/assets/17284229-5ff1-4ae4-9306-81740e63b4cf)|[image](https://github.com/user-attachments/assets/70b4c377-ae83-4620-8cdd-9ca15ea385df)|[image](https://github.com/user-attachments/assets/2ac8711a-eca7-45b2-8099-7df422dba2a1)|[image](https://github.com/user-attachments/assets/4efec2aa-23cb-4f9c-bb16-54d9e75e14cb)|
|__CATÁLOGO__|[catalogo/index](https://www.epublibre.org/catalogo/index)|[image](https://github.com/user-attachments/assets/9be60ed7-50a6-486f-9b96-92f04e076556)|[image](https://github.com/user-attachments/assets/c807dca9-2bbf-4501-bf70-56d2878b8f06)|[image](https://github.com/user-attachments/assets/9578d1e6-8608-4422-9b95-baeee64b1ca1)|[image](https://github.com/user-attachments/assets/12603479-571f-41ab-a13f-14c9059ee92d)|
||[catalogo/index](https://www.epublibre.org/catalogo/index) (búsqueda)|[image](https://github.com/user-attachments/assets/50914379-54c6-4aaf-bc41-9aedd3e17e7c)|[image](https://github.com/user-attachments/assets/051d26ea-29ae-4367-9812-b89eff7744f3)|[image](https://github.com/user-attachments/assets/9f89ecc4-a388-47f2-81da-a961a17aa6f7)|[image](https://github.com/user-attachments/assets/261adce4-1b42-4c97-80b4-3cb70516b7bf)|
|__CATÁLOGO_COL__|[catalogo_col/index](https://www.epublibre.org/catalogo_col/index)|[image](https://github.com/user-attachments/assets/a0226160-05f9-49d1-9f6c-6200adf6d440)|[image](https://github.com/user-attachments/assets/bd0842e6-fa32-4326-97a2-2d669609adf1)|[image](https://github.com/user-attachments/assets/30766963-75e9-4271-a37d-421433b14c2f)|[image](https://github.com/user-attachments/assets/fdde4706-fc9d-4766-ade6-6ecbd4c038b7)|
|__COLECCIÓN__|[coleccion/index/[id]](https://www.epublibre.org/coleccion/index/1534)|[image](https://github.com/user-attachments/assets/904a3f12-6f5e-45f8-afc9-96f8ab74e11c)|[image](https://github.com/user-attachments/assets/729c9ffd-d636-4b4f-860e-41be24922e03)|[image](https://github.com/user-attachments/assets/dc0ed3b6-64d1-4f8c-b182-f09d65b95b7e)|[image](https://github.com/user-attachments/assets/72059fdc-b60a-494b-9768-57db1fc9df83)|
|__DIRECTORIO__|[directorio/index](https://www.epublibre.org/directorio/index)|[image](https://github.com/user-attachments/assets/e18bd789-1ae9-462a-8e2b-fca531d9c2a5)|[image](https://github.com/user-attachments/assets/41a1c711-582d-4efb-986a-83e66a2f5d7d)|[image](https://github.com/user-attachments/assets/5c6bb100-b6ab-430d-b46d-66b1af846204)|[image](https://github.com/user-attachments/assets/889d9c39-c7cf-443a-82e2-08de0ebe2547)|
|__ENCUESTA__|[encuesta/panel](https://www.epublibre.org/encuesta/panel)|[image](https://github.com/user-attachments/assets/7962d221-4826-42d4-bfeb-02e714d77491)|[image](https://github.com/user-attachments/assets/ab2e531c-8095-4333-8f0f-1d1dd9d5942e)|[image](https://github.com/user-attachments/assets/1c6b02f8-4043-4745-a579-fc012b9ae2d8)|[image](https://github.com/user-attachments/assets/c2b5e819-0916-464c-8532-965598e8a896)|
||[encuesta/detalle/[id]](https://www.epublibre.org/encuesta/detalle/37)|[image](https://github.com/user-attachments/assets/83f3646a-33e0-4fc5-98ac-83e962ec99fd)|[image](https://github.com/user-attachments/assets/aeb24483-79df-4874-908c-173f45a16969)|[image](https://github.com/user-attachments/assets/d52f9a17-5b3f-4c61-af48-f2ad935527e1)|[image](https://github.com/user-attachments/assets/88480862-66f9-457c-a00e-b7f5d767a588)|
|__INICIO__|[inicio/index](https://www.epublibre.org/inicio/index)|[image](https://github.com/user-attachments/assets/2f612411-72ca-4cbc-83e4-8254e93771ea)|[image](https://github.com/user-attachments/assets/bd461d9a-592b-4faf-9548-8e68f0a3a516)|[image](https://github.com/user-attachments/assets/afaf23af-ad0d-4c33-876a-369897fe7e53)|[image](https://github.com/user-attachments/assets/188cec03-3ec0-4caa-a534-a8b601ff4366)|
||[inicio/sobrecarga](https://www.epublibre.org/inicio/sobrecarga)|[image](https://github.com/user-attachments/assets/5bcdfac8-0619-4f14-80ca-82c40d8f7c94)|[image](https://github.com/user-attachments/assets/3c166327-72f7-40d0-8131-1b1b96476de3)|[image](https://github.com/user-attachments/assets/19108142-417c-47f4-be7e-c86b1582a021)|[image](https://github.com/user-attachments/assets/feec6ead-6bcd-4ac5-af01-b70a44b417a1)|
||[inicio/manifiesto](https://www.epublibre.org/inicio/manifiesto)|[image](https://github.com/user-attachments/assets/5ad2a83d-c7fd-4b43-97fe-8443cfc9051f)|[image](https://github.com/user-attachments/assets/fec81304-704c-4683-9895-e0a00c80be2f)|[image](https://github.com/user-attachments/assets/c82de933-7f5f-470f-8631-cad35c207690)|[image](https://github.com/user-attachments/assets/3a01b464-64d6-4ae4-a70e-b9be00342bfc)|
|__MANUAL__|[manual/index](https://www.epublibre.org/manual/index)|[image](https://github.com/user-attachments/assets/0ac96d15-4c69-4d7d-8d9d-6b74cd919a2b)|[image](https://github.com/user-attachments/assets/c7ebfb95-7ab4-46d2-a900-c71c4e3519d2)|[image](https://github.com/user-attachments/assets/8fb51fd3-1353-4929-a481-0a6f35fb807d)|[image](https://github.com/user-attachments/assets/71580b06-3d24-47bf-b188-395b8e65900d)|
||[manual/index/faq](https://www.epublibre.org/manual/index/faq)|[image](https://github.com/user-attachments/assets/c03600e5-61ae-41e6-beab-21585ed5de9c)|[image](https://github.com/user-attachments/assets/b055af08-9e07-4959-b6f3-5eb2cec2b6e4)|[image](https://github.com/user-attachments/assets/f934e313-66f3-46ad-845b-abb072ceece0)|[image](https://github.com/user-attachments/assets/b57c7d08-af84-4f7a-a4f1-a5d49bfb3792)|
|__LIBRO__|[libro/detalle/[id]](https://www.epublibre.org/libro/detalle/19293)|[image](https://github.com/user-attachments/assets/70ae847b-f15e-4457-b42d-dfe7ccc4d466)|[image](https://github.com/user-attachments/assets/f51d4072-4413-47dc-891c-24007f46a07c)|[image](https://github.com/user-attachments/assets/b3e8ddbe-34a8-40a1-b6de-716dcabaf052)|[image](https://github.com/user-attachments/assets/f226b850-d2cc-4105-bb12-aa20497aa335)|
|__USUARIO__|[usuario/cuenta](https://www.epublibre.org/usuario/cuenta)||
||[usuario/cuenta/mis_datos](https://www.epublibre.org/usuario/cuenta/mis_datos)||
||[usuario/cuenta/lecturas](https://www.epublibre.org/usuario/cuenta/lecturas)||
||[usuario/cuenta/biblioteca](https://www.epublibre.org/usuario/cuenta/biblioteca)||
||[usuario/cuenta/mensajes](https://www.epublibre.org/usuario/cuenta/mensajes)|[image](https://github.com/user-attachments/assets/dd918f98-3aa6-4586-8be0-1ab2d517c7c2)|[image](https://github.com/user-attachments/assets/9c9d5989-9188-499f-82cc-4a707fde07c5)|[image](https://github.com/user-attachments/assets/0a42e941-1157-4eb5-ba8d-95940887e359)|[image](https://github.com/user-attachments/assets/e423c0e3-ff2c-4a91-8e40-75a865e056c8)|
||[usuario/cuenta/informes_enviados](https://www.epublibre.org/usuario/cuenta/informes_enviados)||
||[usuario/cuenta/aportes](https://www.epublibre.org/usuario/cuenta/aportes)||
||[usuario/cuenta/autores](https://www.epublibre.org/usuario/cuenta/autores)||
||[usuario/cuenta/colecciones](https://www.epublibre.org/usuario/cuenta/colecciones)||
||[usuario/cuenta/premios](https://www.epublibre.org/usuario/cuenta/premios)||
||[usuario/cuenta/informes_erratas](https://www.epublibre.org/usuario/cuenta/informes_erratas)|[image](https://github.com/user-attachments/assets/eec02784-c052-442f-8ff2-806cabfd1ceb)|[image](https://github.com/user-attachments/assets/84fdb4fb-f38b-42db-8623-d25441e305be)|[image](https://github.com/user-attachments/assets/4cdac108-0689-4111-a974-8aad547ecd2f)|[image](https://github.com/user-attachments/assets/468a6811-6190-4667-b3ca-6ceb7aa3a343)|
||[usuario/cuenta/comentarios](https://www.epublibre.org/usuario/cuenta/comentarios)|[image](https://github.com/user-attachments/assets/a774b19f-1977-43b1-9865-90d268ce630d)|[image](https://github.com/user-attachments/assets/1a41e543-2415-4a81-82e0-73188e3dad6b)|[image](https://github.com/user-attachments/assets/1b7b1522-170a-4b21-8fb9-ea4989c56e5c)|[image](https://github.com/user-attachments/assets/44321c61-4f64-4054-945a-526944e9fcf3)|
||[usuario/busqueda_titulos](https://www.epublibre.org/usuario/busqueda_titulos)|[image](https://github.com/user-attachments/assets/6e75b6d3-cb33-4142-96a4-0d62bfb55630)|[image](https://github.com/user-attachments/assets/5fe0a940-1168-4cfe-8766-32310e33e44d)|[image](https://github.com/user-attachments/assets/e4fe5291-4d01-4cd9-bb9b-60707c7f96ab)|[image](https://github.com/user-attachments/assets/4fe13a66-07b7-412f-9465-4d0bc0cbac4e)|
||[usuario/busqueda_titulos](https://www.epublibre.org/usuario/busqueda_titulos) (resultados)||[image](https://github.com/user-attachments/assets/3c1d640b-672e-42dd-a65c-db81ca80cd16)|[image](https://github.com/user-attachments/assets/1a81b57e-6c54-4da1-a3e4-cfc458f77959)|[image](https://github.com/user-attachments/assets/b755f218-7832-4424-a594-b4ae8358d43e)|

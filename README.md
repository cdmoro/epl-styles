# epl-styles

Este proyecto tiene la finalidad de implementar un diseño responsive a la página actual de EPL https://www.epublibre.org

nota: los archivos CSS usados en este proyecto sobreescriben los estilos actuales de Bootstrap.

# Instrucciones

Instrucciones para implentar estos estilos en la web de EPL, en cada página:

1. Agregar `<meta name="viewport" content="width=device-width, initial-scale=1">` en el `head`
2. Agregar el archivo [epl_base.css](src/epl_base.css), ya que contiene estilos comunes a todas las páginas
3. Agregar el archivo correspondiente a cada página

## Probar los estilos en vivo

Para probar los estilos antes de implementarlos definitivamente se pueden usar las herramientas del desarrollador para agregar el tag y los estilos correspondientes en cualquier browswer.

Para hacer pruebas rápidas se pueden usar dos extensiones:
- Meta Viewport Adder para agregar automáticamente el meta tag `viewport` (https://addons.mozilla.org/en-US/firefox/addon/meta-viewport-adder/)
- Stylus para agregar por defecto los estilos necesarios, el base y el específico para cada página (https://addons.mozilla.org/en-US/firefox/addon/styl-us/)

# Paginas

La versión Desktop se mantiene sin cambios y se usa solo como referencia

| Vista | Página | Mobile (428px) | Tablet (810px) | Desktop (940px) |
|:---|:---|:---|:---|:---|
|__ACCESO__|[acceso/login](https://www.epublibre.org/acceso/login)|[image](https://github.com/user-attachments/assets/3306c135-b9fc-4a01-a12c-cafd12ca3273)|[image](https://github.com/user-attachments/assets/a8e7cfc1-75be-4d95-b4c5-9b67891af66b)|[image](https://github.com/user-attachments/assets/e4ee8efa-d58d-43ae-a7ed-3d76fa0fa55b)|
||[acceso/solicitar](https://www.epublibre.org/acceso/solicitar)|[image](https://github.com/user-attachments/assets/23fa04d8-c0c9-43b4-ac81-32fc5b917e68)|[image](https://github.com/user-attachments/assets/2e080616-f7f2-4c31-89b6-743d40aae4ea)|[image](https://github.com/user-attachments/assets/3b0950cf-38f8-43cd-a4c3-b85c819f99c5)|
|__AUTOR__|[autor/index/[id]](https://www.epublibre.org/autor/index/216)|[image](https://github.com/user-attachments/assets/17284229-5ff1-4ae4-9306-81740e63b4cf)|[image](https://github.com/user-attachments/assets/70b4c377-ae83-4620-8cdd-9ca15ea385df)|[image](https://github.com/user-attachments/assets/2ac8711a-eca7-45b2-8099-7df422dba2a1)|
|__CATÁLOGO__|[catalogo/index](https://www.epublibre.org/catalogo/index)|[image](https://github.com/user-attachments/assets/9be60ed7-50a6-486f-9b96-92f04e076556)|[image](https://github.com/user-attachments/assets/c807dca9-2bbf-4501-bf70-56d2878b8f06)|[image](https://github.com/user-attachments/assets/9578d1e6-8608-4422-9b95-baeee64b1ca1)|
||[catalogo/index](https://www.epublibre.org/catalogo/index) (búsqueda)|[image](https://github.com/user-attachments/assets/50914379-54c6-4aaf-bc41-9aedd3e17e7c)|[image](https://github.com/user-attachments/assets/051d26ea-29ae-4367-9812-b89eff7744f3)|[image](https://github.com/user-attachments/assets/9f89ecc4-a388-47f2-81da-a961a17aa6f7)|
|__CATÁLOGO_COL__|[catalogo_col/index](https://www.epublibre.org/catalogo_col/index)|[image](https://github.com/user-attachments/assets/a0226160-05f9-49d1-9f6c-6200adf6d440)|[image](https://github.com/user-attachments/assets/bd0842e6-fa32-4326-97a2-2d669609adf1)|[image](https://github.com/user-attachments/assets/30766963-75e9-4271-a37d-421433b14c2f)|
|__COLECCIÓN__|[coleccion/index/[id]](https://www.epublibre.org/coleccion/index/1534)|[image](https://github.com/user-attachments/assets/904a3f12-6f5e-45f8-afc9-96f8ab74e11c)|[image](https://github.com/user-attachments/assets/729c9ffd-d636-4b4f-860e-41be24922e03)|[image](https://github.com/user-attachments/assets/dc0ed3b6-64d1-4f8c-b182-f09d65b95b7e)|
|__DIRECTORIO__|[directorio/index](https://www.epublibre.org/directorio/index)|[image](https://github.com/user-attachments/assets/e18bd789-1ae9-462a-8e2b-fca531d9c2a5)|[image](https://github.com/user-attachments/assets/41a1c711-582d-4efb-986a-83e66a2f5d7d)|[image](https://github.com/user-attachments/assets/5c6bb100-b6ab-430d-b46d-66b1af846204)|
|__ENCUESTA__|[encuesta/panel](https://www.epublibre.org/encuesta/panel)|
|__INICIO__|[inicio/index](https://www.epublibre.org/inicio/index)|[image](https://github.com/user-attachments/assets/2f612411-72ca-4cbc-83e4-8254e93771ea)|[image](https://github.com/user-attachments/assets/bd461d9a-592b-4faf-9548-8e68f0a3a516)|[image](https://github.com/user-attachments/assets/afaf23af-ad0d-4c33-876a-369897fe7e53)|
||[inicio/sobrecarga](https://www.epublibre.org/inicio/sobrecarga)|
|__MANUAL__|[manual/index](https://www.epublibre.org/manual/index)|[image](https://github.com/user-attachments/assets/0ac96d15-4c69-4d7d-8d9d-6b74cd919a2b)|[image](https://github.com/user-attachments/assets/c7ebfb95-7ab4-46d2-a900-c71c4e3519d2)|[image](https://github.com/user-attachments/assets/8fb51fd3-1353-4929-a481-0a6f35fb807d)|
|__LIBRO__|[libro/detalle/[id]](https://www.epublibre.org/libro/detalle/19293)|[image](https://github.com/user-attachments/assets/70ae847b-f15e-4457-b42d-dfe7ccc4d466)|[image](https://github.com/user-attachments/assets/f51d4072-4413-47dc-891c-24007f46a07c)|[image](https://github.com/user-attachments/assets/b3e8ddbe-34a8-40a1-b6de-716dcabaf052)|
|__USUARIO__|[usuario/cuenta](https://www.epublibre.org/usuario/cuenta)|
||[usuario/cuenta/mis_datos](https://www.epublibre.org/usuario/cuenta/mis_datos)|
||[usuario/cuenta/lecturas](https://www.epublibre.org/usuario/cuenta/lecturas)|
||[usuario/cuenta/biblioteca](https://www.epublibre.org/usuario/cuenta/biblioteca)|
||[usuario/cuenta/mensajes](https://www.epublibre.org/usuario/cuenta/mensajes)|
||[usuario/cuenta/informes_enviados](https://www.epublibre.org/usuario/cuenta/informes_enviados)|
||[usuario/cuenta/aportes](https://www.epublibre.org/usuario/cuenta/aportes)|
||[usuario/cuenta/autores](https://www.epublibre.org/usuario/cuenta/autores)|
||[usuario/cuenta/colecciones](https://www.epublibre.org/usuario/cuenta/colecciones)|
||[usuario/cuenta/premios](https://www.epublibre.org/usuario/cuenta/premios)|
||[usuario/cuenta/informes_erratas](https://www.epublibre.org/usuario/cuenta/informes_erratas)|
||[usuario/cuenta/comentarios](https://www.epublibre.org/usuario/cuenta/comentarios)|
||[usuario/busqueda_titulos](https://www.epublibre.org/usuario/busqueda_titulos)|

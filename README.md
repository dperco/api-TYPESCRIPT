# api-TYPESCRIPT
esta aplicacion es un backend ,del consumo de una Api publica de MercadoLibre , donde consulta  algun tipo de producto  y lo filtra con alguna caracteristicas  .

parado en la carpeta  api-TYPESCRIPT ,ejecutamos primero "npm install"y luego"npm run dev " ,esto levanta  la aplicacion en el port 3001 

desde el navgador  escripbimos la peticion  para el ejemplo son celulares 

       http://127.0.0.1:3001/api/items?q=:celulares
       
       y nos mostrara algo asi 
       
       (https://user-images.githubusercontent.com/87585987/184431213-b565e3cf-66bd-49f0-b911-035cbb13a200.png)
       
       
<!--        si queremos cambiar el producto  hay que cambiar  la  palabre celulres en el  archivo /src/function/index.tsx

 luego si queremos obtener  el detalle de un producto por id  

                     http://127.0.0.1:3001/api/items/MLA1143746497

obtenemos  algo  como esta imagen 

         ![image](https://user-images.githubusercontent.com/87585987/184432340-5789f77e-81b5-4616-8a60-37425466ab4a.png)


en el index de fuctions ,esta la logica 
en el index de routes  las rutas 



  

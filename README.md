
AJAX = Asynchronous JavaScript And XML
=======================================
Server e request send kora and request er aginest a data receive korar kaj ti hosse , AJAX ar.

Frontend theke Backend e API call kora hoi Ajax diye.

Ajax or XMLHttpRequest, Axios, Fetch API = ae sob gulu diyei server e request send hoi and request er 
aginest a akta response receive kori

**** Ajax/axios er vitor API Request kore amra je data gulu pai, segulu HTML body te render/display
 kora hoi , ata kei bole Client-side rendering(CSR).
    

1.React/Vue/SPA- sob kisui chole Ajax Architecture e, akhane je routing gulu hoi, data server e ase
server e data jai, er pisoner main mechanisms hosse Ajax architecture.
2.when javaScript first build, that time javascript could not send data in server. thokhon only webpage er 
modhe kaj korte parto, 
3.porobortite javascript er modhe akta future toiri kora holo, XML http request , er madhome without reloading the webpage/browser directly server e request send kora suru holo and server theke response receive kora gelo. ata k bola hoi AJAX.

AJAX e kaj kora onek ta kosto kor , new object toiri kora, onready kora, request open and send kora etc.porobortite ae AJax er upor base kore new package and library aslo tar nam holo: Axios

Axios hosse Ajax er akta library. axios aser por kaj kora onek easy hoye gelo.

Fetch API: Ajax jokhon ase javaScript at the same time,=== fetch=== nam e akta notun future ane, ata diyeo axios er moto same kaj kora jai. 


*** Browser er URL diye only get requst send kora jai and pison dik diye post back kora jai. onno kisu kora jai na. (put,update,delete) etc.

***so, Browser sarao amader akta http client er proyojon hosse jar dara amra, onno kaj gulu korte pari



//Axios CDN Link: https://cdn.jsdelivr.net/npm/axios/dist/axios.min.js 


*** Backend developer tik kore dibe frontend developer k kivabe server e request send hobe
    API toiri kore dibe Backend developer and frontend developer sei API diye sever e request send korbe
    and request er response receive kore frontend design brower e display korbe


***Ajax/axios  diye amra frontend theke request send kori backend e 
 Practice API:1.Get:    https://crud.teamrabbil.com/api/v1/ReadProduct
              2.Post:   https://crud.teamrabbil.com/api/v1/CreateProduct
              3.update: https://crud.teamrabbil.com/api/v1/UpdateProduct/6395ce12187245c05d68da82
              4.delete: https://crud.teamrabbil.com/api/v1/DeleteProduct/639da5960817590a4e4fd53c
            5.Product_Details: https://crud.teamrabbil.com/api/v1/ReadProductByID/6412ba03f4b1dfe458135769



***API test korar jonno tools link: curl  https://crud.teamrabbil.com/api/v1/ReadProduc 
  Note: curl word ti API link er age dite hoi

server e jodi amra get request send kori tahole likhi: axios.get()         
server e jodi amra post request send kori tahole likhi: axios.post()         
server e jodi amra update request send kori tahole likhi: axios.update()         
server e jodi amra delete request send kori tahole likhi: axios.delete()  


Syntax: axios.get('http://localhost:8000/api/clients')
        .then(function(response){
            console.log(response);
        })
        .catch(function(error){
            console.log(error)
        });


***miligram.css , by default kisu style diye dei, ata css er akta soto package






//jokhon amra kono kisu Delete/Update kori, tokhon id dhore kaj kori.

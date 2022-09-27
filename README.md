<p>
  <a style="text-decoration:none" href="https://github.com/buildingSMART-France/semantics4bim_api">
    <img src="https://img.shields.io/badge/Current Release-Beta-brightgreen" alt="Info" />
  </a>
  <a style="text-decoration:none" href="https://buildingsmartfrance-mediaconstruct.fr//">
    <img src="https://img.shields.io/badge/By-buildingSMART France-blue" alt="bSF" />
  </a>
</p>



# Semantics4BIM API

Semantics4BIM is a platform for easily create, update and manage standards-compliant data dictionaries. More information on https://semantics4bim.com/

## How to start

The current set of APIs can be viewed and tested using Swagger or Postman.

Swagger (Webpage)

- https://app.swaggerhub.com/apis/bSFrance/S4BIM/0.1.1
- Open `AUTH` tab and click `Try it out` and fill your login info in the request body, then click `Execute` button to send the request and get a `token` like { "token": "`ValueOfToken`"} . 
- Click `Authorize` green button in the top and right and fill the `ValueOfToken`.
- And now you can play with all other API with the same logic.  

Postman (Desktop app)

- [Download Postman | Get Started for Free](https://www.postman.com/downloads/)
- Download [Semantics4BIM_Hackathon_v1.postman_collection.json](/Semantics4BIM_Hackathon_v1.postman_collection.json) file
- Import this postman collection file to your Postman
- Open `AUTH` folder and click `AUTHENTICATE` request and fill your login info in the body, then click `Send` button to send the request and get a `token`. 
- Edit collection Semantics4BIM variables and fill your `token` in `JWT` initial value and current v.
- Now, your are all ready for test and play with all other API, have fun !

## Tips

You can directly generate client code in various languages 

- For Swagger : [Generating Code | SwaggerHub Documentation](https://support.smartbear.com/swaggerhub/docs/apis/generating-code/index.html)
- For Postman : [Generating client code | Postman Learning Center](https://learning.postman.com/docs/sending-requests/generate-code-snippets/)

## Documentation

- [Modèles d’objets numériques - buildingSMART France.pdf](https://mediaconstruct.sharepoint.com/:b:/s/Hackathon-Semantics4BIM/EYh7FVo6c7FDtVyWzWPSLl8BjTj-UyiCs39flZSZyLQ0_w?e=zHduW7)
- [Les systèmes de classification et le BIM - buildingSMART France.pdf](https://mediaconstruct.sharepoint.com/:b:/s/Hackathon-Semantics4BIM/ESQYDrxaFsZCrIfXoeTxQ7EBQ5xilqz7OrKYW7BZc3rfkg?e=uftWrO)

## License

Copyright @ [buildingSMART France](https://buildingsmartfrance-mediaconstruct.fr/), 2022
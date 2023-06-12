
## Consommer l 'API
L'API Shiny est une API REST. Si vous avez un doute sur ce qu'est une API REST, n'hésitez pas à jeter un oeil à l'excellent cours [Adoptez les API REST pour vos projets web. 
](https://openclassrooms.com/fr/courses/6573181-adoptez-les-api-rest-pour-vos-projets-web). 
Une fois lancée, cette API met plusieurs routes à votre disposition :

- La route pour récupérer les profils des freelances :
`GET /freelances`

- La route pour avoir le détail d'un profil de freelance :
`GET /profile/?id={id}`

- La route pour avoir le questionnaire :
`GET /survey/`

- La route pour obtenir le résultat du questionnaire :
`GET /results/?a1={answer1}&a2={answer2}&a3={answer3}...`


## Modifier l'API

N'hésitez pas à explorer l'API pour tester. Cette base de code a été initialisée avec [Express Generator](https://expressjs.com/fr/starter/generator.html).
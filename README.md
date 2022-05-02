# test
npm install cypress -D
npm run test  
npm init -y
npm install cypress --save -def
se agrega el script: "cypress:open": "cypress open" en àckage.json
npm run cypress:open


selectores
  // id (selector): #contenido
  // type (selector): selecciona todos los elementos que coincidan con el elemento especificado
  // child (combinador): ejemplo: div > input#username 
  // adjacent sibling: ejemplo: div label + input#username
  // atribute (selector): ejemplo: input[name='password']
  // choosing a specific match: ejemplo: form > did = al div se le agrega nth-chil(1) o child(2) ej: form > divnth-child(1)
  // sub-String Matches: con: ^= match a prefix
                           // $= match a sutfix
                           // *= match a substring(contains)
            //ejmplo: a[targent^=_](empieza) / a[targent$='nk(que termine con nk) / a[targent*='an(busca que tenga an en algun lugar de <a target="_blank" )] ]
            
//https://docs.cypress.io/guides/guides/command-line#How-to-run-commands

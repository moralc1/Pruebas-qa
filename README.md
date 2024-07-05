{
  "id": "9fed32c7-f7ed-43cc-9bef-92c8efd9aec5",
  "version": "2.0",
  "name": "Login inlaze",
  "url": "https://test-qa.inlaze.com/panel",
  "tests": [{
    "id": "d97774b7-da40-42d7-8f66-994c0eaf70a2",
    "name": "1-Registro de usuario exitosamente.",
    "commands": [{
      "id": "782861ad-4d98-4f16-a290-b32701ed7729",
      "comment": "",
      "command": "open",
      "target": "/auth/sign-in",
      "targets": [],
      "value": ""
    }, {
      "id": "36031dc0-cc39-41d3-8054-91d31de10386",
      "comment": "",
      "command": "setWindowSize",
      "target": "1382x744",
      "targets": [],
      "value": ""
    }, {
      "id": "f34ea6b8-7a9a-4c26-a044-357520cda6ca",
      "comment": "",
      "command": "click",
      "target": "linkText=Sign up",
      "targets": [
        ["linkText=Sign up", "linkText"],
        ["css=.text-primary", "css:finder"],
        ["xpath=//a[contains(text(),'Sign up')]", "xpath:link"],
        ["xpath=//a[contains(@href, '/auth/sign-up')]", "xpath:href"],
        ["xpath=//a", "xpath:position"],
        ["xpath=//a[contains(.,'Sign up')]", "xpath:innerText"]
      ],
      "value": ""
    }, {
      "id": "51b86086-5c04-4647-bbf8-48fe89300e7e",
      "comment": "",
      "command": "click",
      "target": "id=full-name",
      "targets": [
        ["id=full-name", "id"],
        ["css=#full-name", "css:finder"],
        ["xpath=//input[@id='full-name']", "xpath:attributes"],
        ["xpath=//input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "bdf953b2-3e92-4d4f-ac9b-4a1a30a0d97d",
      "comment": "",
      "command": "type",
      "target": "id=full-name",
      "targets": [
        ["id=full-name", "id"],
        ["css=#full-name", "css:finder"],
        ["xpath=//input[@id='full-name']", "xpath:attributes"],
        ["xpath=//input", "xpath:position"]
      ],
      "value": "Jaime ruiz"
    }, {
      "id": "a797dbcc-d3fa-47e3-b6a9-63b858f7c991",
      "comment": "",
      "command": "click",
      "target": "id=email",
      "targets": [
        ["id=email", "id"],
        ["css=#email", "css:finder"],
        ["xpath=//input[@id='email']", "xpath:attributes"],
        ["xpath=//div[2]/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "e43b58b8-a8dd-4b62-b769-1eeb39c31441",
      "comment": "",
      "command": "type",
      "target": "id=email",
      "targets": [
        ["id=email", "id"],
        ["css=#email", "css:finder"],
        ["xpath=//input[@id='email']", "xpath:attributes"],
        ["xpath=//div[2]/input", "xpath:position"]
      ],
      "value": "jruiz@gmail.com"
    }, {
      "id": "92dbe74c-4e46-41ad-a3b1-ce11e21a45a5",
      "comment": "",
      "command": "click",
      "target": "css=.w-full > #password",
      "targets": [
        ["css=.w-full > #password", "css:finder"],
        ["xpath=//input[@id='password']", "xpath:attributes"],
        ["xpath=//app-password[@id='password']/div/input", "xpath:idRelative"],
        ["xpath=//app-password/div/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "3b91649d-fee1-4e4d-9176-2435e3db075e",
      "comment": "",
      "command": "type",
      "target": "css=.w-full > #password",
      "targets": [
        ["css=.w-full > #password", "css:finder"],
        ["xpath=//input[@id='password']", "xpath:attributes"],
        ["xpath=//app-password[@id='password']/div/input", "xpath:idRelative"],
        ["xpath=//app-password/div/input", "xpath:position"]
      ],
      "value": "Ruiz2024+"
    }, {
      "id": "ed4bb1cf-e3f7-4814-9f08-72d4b848bfdd",
      "comment": "",
      "command": "click",
      "target": "css=.w-full > #confirm-password",
      "targets": [
        ["css=.w-full > #confirm-password", "css:finder"],
        ["xpath=//input[@id='confirm-password']", "xpath:attributes"],
        ["xpath=//app-password[@id='confirm-password']/div/input", "xpath:idRelative"],
        ["xpath=//div[4]/app-password/div/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "0273bc5c-58be-4c08-ac5e-cd5394b8050e",
      "comment": "",
      "command": "type",
      "target": "css=.w-full > #confirm-password",
      "targets": [
        ["css=.w-full > #confirm-password", "css:finder"],
        ["xpath=//input[@id='confirm-password']", "xpath:attributes"],
        ["xpath=//app-password[@id='confirm-password']/div/input", "xpath:idRelative"],
        ["xpath=//div[4]/app-password/div/input", "xpath:position"]
      ],
      "value": "Ruiz2024+"
    }, {
      "id": "49de0966-9f7e-4c81-91a6-de4fac628001",
      "comment": "",
      "command": "click",
      "target": "css=.btn:nth-child(5)",
      "targets": [
        ["css=.btn:nth-child(5)", "css:finder"],
        ["xpath=//button[@type='submit']", "xpath:attributes"],
        ["xpath=//form/button", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "900482ed-8477-4987-863b-496fb02644c2",
      "comment": "Verifica el msj de registro exitoso",
      "command": "assertText",
      "target": "css=.ml-3",
      "targets": [
        ["css=.ml-3", "css:finder"],
        ["xpath=//div/div[2]", "xpath:position"]
      ],
      "value": "Successful registration!"
    }]
  }, {
    "id": "6c443671-158d-4721-9fd4-0f0f7332df07",
    "name": "2-Regisro de usuario con una sola palabra,",
    "commands": [{
      "id": "d1fccd63-1f78-4e9f-8a37-e9275b49dde9",
      "comment": "",
      "command": "open",
      "target": "/auth/sign-in",
      "targets": [],
      "value": ""
    }, {
      "id": "ef6e6dd4-6b41-444d-90d1-7f558d6365a0",
      "comment": "",
      "command": "setWindowSize",
      "target": "1382x744",
      "targets": [],
      "value": ""
    }, {
      "id": "0d28ab47-2bd9-43c3-8ec9-441d2cc530df",
      "comment": "",
      "command": "click",
      "target": "linkText=Sign up",
      "targets": [
        ["linkText=Sign up", "linkText"],
        ["css=.text-primary", "css:finder"],
        ["xpath=//a[contains(text(),'Sign up')]", "xpath:link"],
        ["xpath=//a[contains(@href, '/auth/sign-up')]", "xpath:href"],
        ["xpath=//a", "xpath:position"],
        ["xpath=//a[contains(.,'Sign up')]", "xpath:innerText"]
      ],
      "value": ""
    }, {
      "id": "18b15c2f-4a2b-4ed8-9ef1-4c89448f1abb",
      "comment": "",
      "command": "click",
      "target": "id=full-name",
      "targets": [
        ["id=full-name", "id"],
        ["css=#full-name", "css:finder"],
        ["xpath=//input[@id='full-name']", "xpath:attributes"],
        ["xpath=//input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "ff483f70-5d70-4ba1-b64e-f7306144eed5",
      "comment": "",
      "command": "type",
      "target": "id=full-name",
      "targets": [
        ["id=full-name", "id"],
        ["css=#full-name", "css:finder"],
        ["xpath=//input[@id='full-name']", "xpath:attributes"],
        ["xpath=//input", "xpath:position"]
      ],
      "value": "Jorge"
    }, {
      "id": "a4c8be79-8524-4b9f-9a38-384f645350ab",
      "comment": "",
      "command": "click",
      "target": "id=email",
      "targets": [
        ["id=email", "id"],
        ["css=#email", "css:finder"],
        ["xpath=//input[@id='email']", "xpath:attributes"],
        ["xpath=//div[2]/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "a485583f-4a4b-4ed0-8eaf-8e5d54204934",
      "comment": "",
      "command": "type",
      "target": "id=email",
      "targets": [
        ["id=email", "id"],
        ["css=#email", "css:finder"],
        ["xpath=//input[@id='email']", "xpath:attributes"],
        ["xpath=//div[2]/input", "xpath:position"]
      ],
      "value": "cgomez@gmail.com"
    }, {
      "id": "c8f901a9-b27f-4b33-b022-f271e24a9164",
      "comment": "",
      "command": "click",
      "target": "css=.w-full > #password",
      "targets": [
        ["css=.w-full > #password", "css:finder"],
        ["xpath=//input[@id='password']", "xpath:attributes"],
        ["xpath=//app-password[@id='password']/div/input", "xpath:idRelative"],
        ["xpath=//app-password/div/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "392b0c0d-0f40-4167-af07-0d4343e3ac42",
      "comment": "",
      "command": "type",
      "target": "css=.w-full > #password",
      "targets": [
        ["css=.w-full > #password", "css:finder"],
        ["xpath=//input[@id='password']", "xpath:attributes"],
        ["xpath=//app-password[@id='password']/div/input", "xpath:idRelative"],
        ["xpath=//app-password/div/input", "xpath:position"]
      ],
      "value": "Morales2024+"
    }, {
      "id": "ef2637cf-6994-4960-bcba-108a38c12ec8",
      "comment": "",
      "command": "click",
      "target": "css=.w-full > #confirm-password",
      "targets": [
        ["css=.w-full > #confirm-password", "css:finder"],
        ["xpath=//input[@id='confirm-password']", "xpath:attributes"],
        ["xpath=//app-password[@id='confirm-password']/div/input", "xpath:idRelative"],
        ["xpath=//div[4]/app-password/div/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "6604e3fc-0492-4986-ae20-ea6e50c2c2a1",
      "comment": "",
      "command": "type",
      "target": "css=.w-full > #confirm-password",
      "targets": [
        ["css=.w-full > #confirm-password", "css:finder"],
        ["xpath=//input[@id='confirm-password']", "xpath:attributes"],
        ["xpath=//app-password[@id='confirm-password']/div/input", "xpath:idRelative"],
        ["xpath=//div[4]/app-password/div/input", "xpath:position"]
      ],
      "value": "Morales2024+"
    }, {
      "id": "276d9cdf-152d-4feb-981c-76b4816c3bdc",
      "comment": "",
      "command": "click",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "6bcf0826-dc81-450f-a67a-e1baa862559b",
      "comment": "",
      "command": "click",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }]
  }, {
    "id": "afdce441-ce8d-471e-a5da-681d051a39e8",
    "name": "3-Registro con correo no standar",
    "commands": [{
      "id": "84864908-257a-492a-a01d-620cd726433e",
      "comment": "",
      "command": "open",
      "target": "/auth/sign-in",
      "targets": [],
      "value": ""
    }, {
      "id": "6bbb9a34-38ca-419c-9f9a-24e1fa12bb8e",
      "comment": "",
      "command": "setWindowSize",
      "target": "1382x744",
      "targets": [],
      "value": ""
    }, {
      "id": "a16ed9bc-0a12-4cf4-8914-082d76efe0ef",
      "comment": "",
      "command": "click",
      "target": "linkText=Sign up",
      "targets": [
        ["linkText=Sign up", "linkText"],
        ["css=.text-primary", "css:finder"],
        ["xpath=//a[contains(text(),'Sign up')]", "xpath:link"],
        ["xpath=//a[contains(@href, '/auth/sign-up')]", "xpath:href"],
        ["xpath=//a", "xpath:position"],
        ["xpath=//a[contains(.,'Sign up')]", "xpath:innerText"]
      ],
      "value": ""
    }, {
      "id": "f784dcab-43e8-4cfb-a379-3cc5ba6b69e6",
      "comment": "",
      "command": "click",
      "target": "id=full-name",
      "targets": [
        ["id=full-name", "id"],
        ["css=#full-name", "css:finder"],
        ["xpath=//input[@id='full-name']", "xpath:attributes"],
        ["xpath=//input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "bf46afc3-4bc1-4f54-8efb-6d50b645c12d",
      "comment": "",
      "command": "type",
      "target": "id=full-name",
      "targets": [
        ["id=full-name", "id"],
        ["css=#full-name", "css:finder"],
        ["xpath=//input[@id='full-name']", "xpath:attributes"],
        ["xpath=//input", "xpath:position"]
      ],
      "value": "Camilo diaz"
    }, {
      "id": "903516df-d457-4823-8d83-1ebd77ae6eab",
      "comment": "",
      "command": "click",
      "target": "id=email",
      "targets": [
        ["id=email", "id"],
        ["css=#email", "css:finder"],
        ["xpath=//input[@id='email']", "xpath:attributes"],
        ["xpath=//div[2]/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "a86b3be9-0c28-4241-b69b-b0f11198ac40",
      "comment": "",
      "command": "type",
      "target": "id=email",
      "targets": [
        ["id=email", "id"],
        ["css=#email", "css:finder"],
        ["xpath=//input[@id='email']", "xpath:attributes"],
        ["xpath=//div[2]/input", "xpath:position"]
      ],
      "value": "cdiaz-123.com"
    }, {
      "id": "5d2e51ba-f65f-4fcc-a568-90e4b6ca1332",
      "comment": "",
      "command": "click",
      "target": "css=.w-full > #password",
      "targets": [
        ["css=.w-full > #password", "css:finder"],
        ["xpath=//input[@id='password']", "xpath:attributes"],
        ["xpath=//app-password[@id='password']/div/input", "xpath:idRelative"],
        ["xpath=//app-password/div/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "eee05bc8-4a07-4473-a80f-55ad7039f740",
      "comment": "",
      "command": "type",
      "target": "css=.w-full > #password",
      "targets": [
        ["css=.w-full > #password", "css:finder"],
        ["xpath=//input[@id='password']", "xpath:attributes"],
        ["xpath=//app-password[@id='password']/div/input", "xpath:idRelative"],
        ["xpath=//app-password/div/input", "xpath:position"]
      ],
      "value": "Cdiaz2024+"
    }, {
      "id": "4cfa18b1-7396-404b-83ca-003d1fba2e43",
      "comment": "",
      "command": "click",
      "target": "css=.w-full > #confirm-password",
      "targets": [
        ["css=.w-full > #confirm-password", "css:finder"],
        ["xpath=//input[@id='confirm-password']", "xpath:attributes"],
        ["xpath=//app-password[@id='confirm-password']/div/input", "xpath:idRelative"],
        ["xpath=//div[4]/app-password/div/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "9ef446ef-8f33-468f-b1c2-70caacd32f6f",
      "comment": "",
      "command": "type",
      "target": "css=.w-full > #confirm-password",
      "targets": [
        ["css=.w-full > #confirm-password", "css:finder"],
        ["xpath=//input[@id='confirm-password']", "xpath:attributes"],
        ["xpath=//app-password[@id='confirm-password']/div/input", "xpath:idRelative"],
        ["xpath=//div[4]/app-password/div/input", "xpath:position"]
      ],
      "value": "Cdiaz2024+"
    }, {
      "id": "1963f4df-f7cc-4c82-9c54-1fadb24af0de",
      "comment": "",
      "command": "click",
      "target": "css=.btn:nth-child(5)",
      "targets": [
        ["css=.btn:nth-child(5)", "css:finder"],
        ["xpath=//button[@type='submit']", "xpath:attributes"],
        ["xpath=//form/button", "xpath:position"]
      ],
      "value": ""
    }]
  }, {
    "id": "5298b80d-6702-475b-99fc-ebdaacd6ec3a",
    "name": "4-Registro con contraseñas diferentes en confirmación",
    "commands": [{
      "id": "00323ba1-81df-4ccd-95cb-139c5cada3dc",
      "comment": "",
      "command": "open",
      "target": "/auth/sign-in",
      "targets": [],
      "value": ""
    }, {
      "id": "6a5559cf-db03-47f5-9ef5-2c80291ef4f0",
      "comment": "",
      "command": "setWindowSize",
      "target": "1382x744",
      "targets": [],
      "value": ""
    }, {
      "id": "baac2329-3ebd-4453-b867-2b50bf35c4fe",
      "comment": "",
      "command": "click",
      "target": "linkText=Sign up",
      "targets": [
        ["linkText=Sign up", "linkText"],
        ["css=.text-primary", "css:finder"],
        ["xpath=//a[contains(text(),'Sign up')]", "xpath:link"],
        ["xpath=//a[contains(@href, '/auth/sign-up')]", "xpath:href"],
        ["xpath=//a", "xpath:position"],
        ["xpath=//a[contains(.,'Sign up')]", "xpath:innerText"]
      ],
      "value": ""
    }, {
      "id": "84514f03-ed15-4c80-9825-72640ce7ce3c",
      "comment": "",
      "command": "click",
      "target": "id=full-name",
      "targets": [
        ["id=full-name", "id"],
        ["css=#full-name", "css:finder"],
        ["xpath=//input[@id='full-name']", "xpath:attributes"],
        ["xpath=//input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "915be823-a6d5-4b98-a637-e13116211080",
      "comment": "",
      "command": "type",
      "target": "id=full-name",
      "targets": [
        ["id=full-name", "id"],
        ["css=#full-name", "css:finder"],
        ["xpath=//input[@id='full-name']", "xpath:attributes"],
        ["xpath=//input", "xpath:position"]
      ],
      "value": "Camilo diaz"
    }, {
      "id": "993492f5-65b2-4d73-8c6d-ae06552855ac",
      "comment": "",
      "command": "click",
      "target": "id=email",
      "targets": [
        ["id=email", "id"],
        ["css=#email", "css:finder"],
        ["xpath=//input[@id='email']", "xpath:attributes"],
        ["xpath=//div[2]/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "0c728528-de6b-4393-9832-cec0b265f3c0",
      "comment": "",
      "command": "type",
      "target": "id=email",
      "targets": [
        ["id=email", "id"],
        ["css=#email", "css:finder"],
        ["xpath=//input[@id='email']", "xpath:attributes"],
        ["xpath=//div[2]/input", "xpath:position"]
      ],
      "value": "cgomez@gmail.com"
    }, {
      "id": "9044a003-4998-422d-a0e3-9495614ddc09",
      "comment": "",
      "command": "click",
      "target": "css=.w-full > #password",
      "targets": [
        ["css=.w-full > #password", "css:finder"],
        ["xpath=//input[@id='password']", "xpath:attributes"],
        ["xpath=//app-password[@id='password']/div/input", "xpath:idRelative"],
        ["xpath=//app-password/div/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "5ff639b0-38b4-4ce7-824a-71d8e581e53c",
      "comment": "",
      "command": "type",
      "target": "css=.w-full > #password",
      "targets": [
        ["css=.w-full > #password", "css:finder"],
        ["xpath=//input[@id='password']", "xpath:attributes"],
        ["xpath=//app-password[@id='password']/div/input", "xpath:idRelative"],
        ["xpath=//app-password/div/input", "xpath:position"]
      ],
      "value": "Cdiaz2024+"
    }, {
      "id": "efc80efe-5da2-4f7c-b81f-5bc56421b929",
      "comment": "",
      "command": "click",
      "target": "css=#password .fa-solid",
      "targets": [
        ["css=#password .fa-solid", "css:finder"],
        ["xpath=//app-password[@id='password']/div/button/i", "xpath:idRelative"],
        ["xpath=//i", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "7cc36331-b2e5-42c5-be6c-3bc600dcf69e",
      "comment": "",
      "command": "click",
      "target": "css=.w-full > #confirm-password",
      "targets": [
        ["css=.w-full > #confirm-password", "css:finder"],
        ["xpath=//input[@id='confirm-password']", "xpath:attributes"],
        ["xpath=//app-password[@id='confirm-password']/div/input", "xpath:idRelative"],
        ["xpath=//div[4]/app-password/div/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "5eb6bac7-59f7-4b2e-9a83-1740b4d2ded2",
      "comment": "",
      "command": "type",
      "target": "css=.w-full > #confirm-password",
      "targets": [
        ["css=.w-full > #confirm-password", "css:finder"],
        ["xpath=//input[@id='confirm-password']", "xpath:attributes"],
        ["xpath=//app-password[@id='confirm-password']/div/input", "xpath:idRelative"],
        ["xpath=//div[4]/app-password/div/input", "xpath:position"]
      ],
      "value": "Cdiaz2023+"
    }, {
      "id": "f63e5950-6268-45a5-b4af-fdd24d4e9944",
      "comment": "",
      "command": "click",
      "target": "css=#confirm-password .btn",
      "targets": [
        ["css=#confirm-password .btn", "css:finder"],
        ["xpath=(//button[@type='button'])[2]", "xpath:attributes"],
        ["xpath=//app-password[@id='confirm-password']/div/button", "xpath:idRelative"],
        ["xpath=//div[4]/app-password/div/button", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "ed3e7013-3b43-4ac1-b23a-647e40fa0d73",
      "comment": "",
      "command": "assertText",
      "target": "css=.label-text-alt",
      "targets": [
        ["css=.label-text-alt", "css:finder"],
        ["xpath=//label[2]/span", "xpath:position"],
        ["xpath=//span[contains(.,'Passwords do not match')]", "xpath:innerText"]
      ],
      "value": "Passwords do not match"
    }]
  }, {
    "id": "04ddc211-44ef-4dd6-b22a-87bfbbd29e43",
    "name": "5-Envio de formulario con dato faltante (Contraseña de confirmación)",
    "commands": [{
      "id": "a4fa2ba6-d87a-4a4b-9c91-fb09f238d7c5",
      "comment": "",
      "command": "open",
      "target": "/auth/sign-in",
      "targets": [],
      "value": ""
    }, {
      "id": "8e9896dd-51b5-46b5-9a7b-5a0df699f056",
      "comment": "",
      "command": "setWindowSize",
      "target": "1366x728",
      "targets": [],
      "value": ""
    }, {
      "id": "2f2137a5-8325-4225-abe7-46fbda2c89f6",
      "comment": "",
      "command": "click",
      "target": "linkText=Sign up",
      "targets": [
        ["linkText=Sign up", "linkText"],
        ["css=.text-primary", "css:finder"],
        ["xpath=//a[contains(text(),'Sign up')]", "xpath:link"],
        ["xpath=//a[contains(@href, '/auth/sign-up')]", "xpath:href"],
        ["xpath=//a", "xpath:position"],
        ["xpath=//a[contains(.,'Sign up')]", "xpath:innerText"]
      ],
      "value": ""
    }, {
      "id": "a8b0c773-6b4a-4705-a7fb-082c2af35a88",
      "comment": "",
      "command": "click",
      "target": "id=full-name",
      "targets": [
        ["id=full-name", "id"],
        ["css=#full-name", "css:finder"],
        ["xpath=//input[@id='full-name']", "xpath:attributes"],
        ["xpath=//input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "763ac515-b7ae-4523-b8cd-dd27d86e486f",
      "comment": "",
      "command": "type",
      "target": "id=full-name",
      "targets": [
        ["id=full-name", "id"],
        ["css=#full-name", "css:finder"],
        ["xpath=//input[@id='full-name']", "xpath:attributes"],
        ["xpath=//input", "xpath:position"]
      ],
      "value": "Sonia Nova"
    }, {
      "id": "233c6653-c580-4cab-8d32-14b391756c49",
      "comment": "",
      "command": "click",
      "target": "id=email",
      "targets": [
        ["id=email", "id"],
        ["css=#email", "css:finder"],
        ["xpath=//input[@id='email']", "xpath:attributes"],
        ["xpath=//div[2]/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "2009c732-f493-4615-a077-b1797f1a1b0a",
      "comment": "",
      "command": "type",
      "target": "id=email",
      "targets": [
        ["id=email", "id"],
        ["css=#email", "css:finder"],
        ["xpath=//input[@id='email']", "xpath:attributes"],
        ["xpath=//div[2]/input", "xpath:position"]
      ],
      "value": "cdiaz@123.com"
    }, {
      "id": "da722c69-5fae-405e-9ae5-1b61e8a0e679",
      "comment": "",
      "command": "click",
      "target": "css=.w-full > #password",
      "targets": [
        ["css=.w-full > #password", "css:finder"],
        ["xpath=//input[@id='password']", "xpath:attributes"],
        ["xpath=//app-password[@id='password']/div/input", "xpath:idRelative"],
        ["xpath=//app-password/div/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "c34aeaa6-e407-4eec-b9d0-18ae8ff75839",
      "comment": "",
      "command": "type",
      "target": "css=.w-full > #password",
      "targets": [
        ["css=.w-full > #password", "css:finder"],
        ["xpath=//input[@id='password']", "xpath:attributes"],
        ["xpath=//app-password[@id='password']/div/input", "xpath:idRelative"],
        ["xpath=//app-password/div/input", "xpath:position"]
      ],
      "value": "Snova2'24+"
    }, {
      "id": "3f0550f8-9c18-4345-9f94-81ba6c8cff12",
      "comment": "",
      "command": "click",
      "target": "css=.w-full > #confirm-password",
      "targets": [
        ["css=.w-full > #confirm-password", "css:finder"],
        ["xpath=//input[@id='confirm-password']", "xpath:attributes"],
        ["xpath=//app-password[@id='confirm-password']/div/input", "xpath:idRelative"],
        ["xpath=//div[4]/app-password/div/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "657bec82-c636-41d1-9ed6-b58a5d21bb42",
      "comment": "",
      "command": "click",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "121f9c57-226c-488b-a91f-086a6bb4e4c1",
      "comment": "",
      "command": "click",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "3b28849f-170a-47b1-a2a4-64ec6aafb648",
      "comment": "",
      "command": "click",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "f93213ed-6234-4b76-a80d-3a7490add80a",
      "comment": "",
      "command": "doubleClick",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "b17c13d3-b57d-4a04-a5e9-4ee118f60789",
      "comment": "",
      "command": "click",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "a4ae7f69-c1ec-486b-bf6d-d0dcd749559d",
      "comment": "",
      "command": "click",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "207e1801-5a86-40d2-91d9-e0e5c109691a",
      "comment": "",
      "command": "click",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "0445595e-c1c9-4f16-b4a3-30b5653b8281",
      "comment": "",
      "command": "click",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "c975bfc1-dfed-4673-8513-2a3ecc60d6ca",
      "comment": "",
      "command": "doubleClick",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "303b2623-041e-4c04-9297-35ee12b374ca",
      "comment": "",
      "command": "click",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "98d7dc9c-9f38-45e9-a16a-b07e6593783b",
      "comment": "",
      "command": "click",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "bbca404a-c40d-4067-9e9d-72d51184e8fb",
      "comment": "",
      "command": "doubleClick",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }]
  }, {
    "id": "9019d255-fe44-4093-b881-120e31fd510e",
    "name": "11-Envio de formulario con dato faltante (Contraseña inicial)",
    "commands": [{
      "id": "b8318b38-467d-466b-b98c-b3f7c1cc430b",
      "comment": "",
      "command": "open",
      "target": "/auth/sign-in",
      "targets": [],
      "value": ""
    }, {
      "id": "ecd9583e-2906-44d2-af9e-d09d2ad608fe",
      "comment": "",
      "command": "setWindowSize",
      "target": "1366x728",
      "targets": [],
      "value": ""
    }, {
      "id": "904c2293-4735-47bf-b41d-e3732c93f2ec",
      "comment": "",
      "command": "click",
      "target": "linkText=Sign up",
      "targets": [
        ["linkText=Sign up", "linkText"],
        ["css=.text-primary", "css:finder"],
        ["xpath=//a[contains(text(),'Sign up')]", "xpath:link"],
        ["xpath=//a[contains(@href, '/auth/sign-up')]", "xpath:href"],
        ["xpath=//a", "xpath:position"],
        ["xpath=//a[contains(.,'Sign up')]", "xpath:innerText"]
      ],
      "value": ""
    }, {
      "id": "e77a5a14-f2a5-4627-893e-425f7baa7a8a",
      "comment": "",
      "command": "click",
      "target": "id=full-name",
      "targets": [
        ["id=full-name", "id"],
        ["css=#full-name", "css:finder"],
        ["xpath=//input[@id='full-name']", "xpath:attributes"],
        ["xpath=//input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "2ccfa174-2024-4f38-a73e-dd53c8d2e100",
      "comment": "",
      "command": "type",
      "target": "id=full-name",
      "targets": [
        ["id=full-name", "id"],
        ["css=#full-name", "css:finder"],
        ["xpath=//input[@id='full-name']", "xpath:attributes"],
        ["xpath=//input", "xpath:position"]
      ],
      "value": "Alejandra Perez"
    }, {
      "id": "7ac0f193-54f0-4b3a-ad18-975c82c4d268",
      "comment": "",
      "command": "click",
      "target": "id=email",
      "targets": [
        ["id=email", "id"],
        ["css=#email", "css:finder"],
        ["xpath=//input[@id='email']", "xpath:attributes"],
        ["xpath=//div[2]/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "5b698325-89e8-43e5-bcd4-1753e4755a21",
      "comment": "",
      "command": "type",
      "target": "id=email",
      "targets": [
        ["id=email", "id"],
        ["css=#email", "css:finder"],
        ["xpath=//input[@id='email']", "xpath:attributes"],
        ["xpath=//div[2]/input", "xpath:position"]
      ],
      "value": "Aperez@gmail.com"
    }, {
      "id": "6aa5899b-0dab-48b5-8a4a-9e22bd0af464",
      "comment": "",
      "command": "click",
      "target": "css=.w-full > #confirm-password",
      "targets": [
        ["css=.w-full > #confirm-password", "css:finder"],
        ["xpath=//input[@id='confirm-password']", "xpath:attributes"],
        ["xpath=//app-password[@id='confirm-password']/div/input", "xpath:idRelative"],
        ["xpath=//div[4]/app-password/div/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "b936c304-4fae-4717-8ab1-24a8b96164f9",
      "comment": "",
      "command": "type",
      "target": "css=.w-full > #confirm-password",
      "targets": [
        ["css=.w-full > #confirm-password", "css:finder"],
        ["xpath=//input[@id='confirm-password']", "xpath:attributes"],
        ["xpath=//app-password[@id='confirm-password']/div/input", "xpath:idRelative"],
        ["xpath=//div[4]/app-password/div/input", "xpath:position"]
      ],
      "value": "Aperez2024+"
    }, {
      "id": "f5f05415-3543-4492-bc8d-a3328241a78a",
      "comment": "",
      "command": "click",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "78b72134-bd43-4052-a463-00d89560b234",
      "comment": "",
      "command": "click",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "d9c9099f-b945-45d8-b8f2-03c1294067b0",
      "comment": "",
      "command": "doubleClick",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "cc6c9ce0-5d35-4bee-a8a8-20ba2463eeaf",
      "comment": "",
      "command": "click",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "62adbf9a-cf81-4a47-b777-4cd345b1f22e",
      "comment": "",
      "command": "click",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "14e127ab-a489-4584-bd4a-41db27606740",
      "comment": "",
      "command": "click",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "32519cd4-72c8-4dd0-bb21-af8381bbb97a",
      "comment": "",
      "command": "click",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "43058111-451b-42b6-b085-8a144c9e2237",
      "comment": "",
      "command": "click",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }]
  }, {
    "id": "cf50b3be-d7c4-409c-b259-6584cc506839",
    "name": "10-Envio de formulario con dato faltante (Correo)",
    "commands": [{
      "id": "a217cb6e-9caf-4bb5-ad5c-842aba87cc4b",
      "comment": "",
      "command": "open",
      "target": "/auth/sign-in",
      "targets": [],
      "value": ""
    }, {
      "id": "7c58de66-3fea-4077-9e0c-d631b2c64ea1",
      "comment": "",
      "command": "setWindowSize",
      "target": "1366x728",
      "targets": [],
      "value": ""
    }, {
      "id": "d6aae124-f9cf-4de1-bb2a-291f4eb75c89",
      "comment": "",
      "command": "click",
      "target": "linkText=Sign up",
      "targets": [
        ["linkText=Sign up", "linkText"],
        ["css=.text-primary", "css:finder"],
        ["xpath=//a[contains(text(),'Sign up')]", "xpath:link"],
        ["xpath=//a[contains(@href, '/auth/sign-up')]", "xpath:href"],
        ["xpath=//a", "xpath:position"],
        ["xpath=//a[contains(.,'Sign up')]", "xpath:innerText"]
      ],
      "value": ""
    }, {
      "id": "91b8c540-3192-4d97-9223-fcbb319cc271",
      "comment": "",
      "command": "click",
      "target": "id=full-name",
      "targets": [
        ["id=full-name", "id"],
        ["css=#full-name", "css:finder"],
        ["xpath=//input[@id='full-name']", "xpath:attributes"],
        ["xpath=//input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "f76ff738-d554-4841-b354-30feffd83d81",
      "comment": "",
      "command": "type",
      "target": "id=full-name",
      "targets": [
        ["id=full-name", "id"],
        ["css=#full-name", "css:finder"],
        ["xpath=//input[@id='full-name']", "xpath:attributes"],
        ["xpath=//input", "xpath:position"]
      ],
      "value": "Sandra Urquijo"
    }, {
      "id": "55b4aafa-f7d5-447f-a3db-cc486df418fe",
      "comment": "",
      "command": "click",
      "target": "css=.w-full > #password",
      "targets": [
        ["css=.w-full > #password", "css:finder"],
        ["xpath=//input[@id='password']", "xpath:attributes"],
        ["xpath=//app-password[@id='password']/div/input", "xpath:idRelative"],
        ["xpath=//app-password/div/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "eada4b47-5357-471a-87bd-9217ac6f38c3",
      "comment": "",
      "command": "type",
      "target": "css=.w-full > #password",
      "targets": [
        ["css=.w-full > #password", "css:finder"],
        ["xpath=//input[@id='password']", "xpath:attributes"],
        ["xpath=//app-password[@id='password']/div/input", "xpath:idRelative"],
        ["xpath=//app-password/div/input", "xpath:position"]
      ],
      "value": "Urquijo2024+"
    }, {
      "id": "a3d39492-bb1d-4510-8340-ea312f7326ce",
      "comment": "",
      "command": "click",
      "target": "css=.w-full > #confirm-password",
      "targets": [
        ["css=.w-full > #confirm-password", "css:finder"],
        ["xpath=//input[@id='confirm-password']", "xpath:attributes"],
        ["xpath=//app-password[@id='confirm-password']/div/input", "xpath:idRelative"],
        ["xpath=//div[4]/app-password/div/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "387133ec-38d8-48fc-ab49-940941f7f9d9",
      "comment": "",
      "command": "type",
      "target": "css=.w-full > #confirm-password",
      "targets": [
        ["css=.w-full > #confirm-password", "css:finder"],
        ["xpath=//input[@id='confirm-password']", "xpath:attributes"],
        ["xpath=//app-password[@id='confirm-password']/div/input", "xpath:idRelative"],
        ["xpath=//div[4]/app-password/div/input", "xpath:position"]
      ],
      "value": "Urquijo2024+"
    }, {
      "id": "58eb1b87-7e1f-4b53-bffd-59c85d406a02",
      "comment": "",
      "command": "click",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "67c0d57a-7c8a-4487-827e-cf9880908f23",
      "comment": "",
      "command": "click",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "019cffb4-5b56-4b98-a15a-a9e6db074da4",
      "comment": "",
      "command": "doubleClick",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "90904ce1-ab75-4b68-9a53-fbffa4ec4409",
      "comment": "",
      "command": "click",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "c5e8b1b3-3056-4bbc-a6ce-3eaf516609c5",
      "comment": "",
      "command": "click",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "4047a62c-3c62-4dcf-9c9d-a78642f2737c",
      "comment": "",
      "command": "doubleClick",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "1316fae6-4238-451b-b4af-3db1cdd7e72e",
      "comment": "",
      "command": "click",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "fd413bd4-a4c7-4a19-bd69-36aaa66e6061",
      "comment": "",
      "command": "click",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "200b2f6f-1213-43d0-808d-d7b318741c8d",
      "comment": "",
      "command": "click",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "02d45e6e-96d4-41f3-b29b-e28a22bd6f45",
      "comment": "",
      "command": "click",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "7cfba347-5dbb-4434-990b-3e6f0220708f",
      "comment": "",
      "command": "doubleClick",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }]
  }, {
    "id": "51850228-b8b4-477d-938a-a0e792127f5f",
    "name": "12-Envio de formulario con dato faltante (Nombre y apellido)",
    "commands": [{
      "id": "383c8e00-f69c-4c2c-bb0b-d7bf6389de5c",
      "comment": "",
      "command": "open",
      "target": "/auth/sign-in",
      "targets": [],
      "value": ""
    }, {
      "id": "1b3529c0-8031-416c-825a-d01181336291",
      "comment": "",
      "command": "setWindowSize",
      "target": "1366x728",
      "targets": [],
      "value": ""
    }, {
      "id": "be1953b4-7e52-4290-887c-bc806a9c21cb",
      "comment": "",
      "command": "click",
      "target": "linkText=Sign up",
      "targets": [
        ["linkText=Sign up", "linkText"],
        ["css=.text-primary", "css:finder"],
        ["xpath=//a[contains(text(),'Sign up')]", "xpath:link"],
        ["xpath=//a[contains(@href, '/auth/sign-up')]", "xpath:href"],
        ["xpath=//a", "xpath:position"],
        ["xpath=//a[contains(.,'Sign up')]", "xpath:innerText"]
      ],
      "value": ""
    }, {
      "id": "47017ace-cc0a-4411-8c8d-ff237496d2d0",
      "comment": "",
      "command": "click",
      "target": "id=email",
      "targets": [
        ["id=email", "id"],
        ["css=#email", "css:finder"],
        ["xpath=//input[@id='email']", "xpath:attributes"],
        ["xpath=//div[2]/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "1f15dfd3-8c0b-4702-816c-8c3e50be51c0",
      "comment": "",
      "command": "type",
      "target": "id=email",
      "targets": [
        ["id=email", "id"],
        ["css=#email", "css:finder"],
        ["xpath=//input[@id='email']", "xpath:attributes"],
        ["xpath=//div[2]/input", "xpath:position"]
      ],
      "value": "jruiz@gmail.com"
    }, {
      "id": "4a58844e-b601-4987-be71-6e6c6823e136",
      "comment": "",
      "command": "click",
      "target": "css=.w-full > #password",
      "targets": [
        ["css=.w-full > #password", "css:finder"],
        ["xpath=//input[@id='password']", "xpath:attributes"],
        ["xpath=//app-password[@id='password']/div/input", "xpath:idRelative"],
        ["xpath=//app-password/div/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "fa6e77f6-136a-409c-b04f-8af38b48790b",
      "comment": "",
      "command": "type",
      "target": "css=.w-full > #password",
      "targets": [
        ["css=.w-full > #password", "css:finder"],
        ["xpath=//input[@id='password']", "xpath:attributes"],
        ["xpath=//app-password[@id='password']/div/input", "xpath:idRelative"],
        ["xpath=//app-password/div/input", "xpath:position"]
      ],
      "value": "Morales2024+"
    }, {
      "id": "c3820f2a-e754-4a9c-b064-a1fd4249e866",
      "comment": "",
      "command": "click",
      "target": "css=.w-full > #confirm-password",
      "targets": [
        ["css=.w-full > #confirm-password", "css:finder"],
        ["xpath=//input[@id='confirm-password']", "xpath:attributes"],
        ["xpath=//app-password[@id='confirm-password']/div/input", "xpath:idRelative"],
        ["xpath=//div[4]/app-password/div/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "3b8ab422-588d-4782-babc-67083c1c11a7",
      "comment": "",
      "command": "type",
      "target": "css=.w-full > #confirm-password",
      "targets": [
        ["css=.w-full > #confirm-password", "css:finder"],
        ["xpath=//input[@id='confirm-password']", "xpath:attributes"],
        ["xpath=//app-password[@id='confirm-password']/div/input", "xpath:idRelative"],
        ["xpath=//div[4]/app-password/div/input", "xpath:position"]
      ],
      "value": "Mrales2024"
    }, {
      "id": "1ee6e90e-7beb-436a-868f-93beab3fe134",
      "comment": "",
      "command": "click",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "95e516c3-c0a4-4a70-8def-5aad3882212a",
      "comment": "",
      "command": "click",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "9642c932-579c-4a64-b04f-64a93662f8b3",
      "comment": "",
      "command": "doubleClick",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "4e8f7da5-e210-4c8b-a440-df49e27d1f0f",
      "comment": "",
      "command": "click",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "12ab7542-6d19-430e-a917-4fc30eee28b3",
      "comment": "",
      "command": "click",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "6947fc45-7e66-4f43-91d8-dd70053d6f23",
      "comment": "",
      "command": "doubleClick",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "cae0761f-5fcc-49ae-afd4-797192669518",
      "comment": "",
      "command": "click",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "8e14dd91-287c-432e-b856-9d0f7f6b938f",
      "comment": "",
      "command": "click",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "f89383c0-1c93-4e2a-8ecc-d10dbbf9145e",
      "comment": "",
      "command": "doubleClick",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "d20105fa-0a12-4ad9-8f31-2c1c8c0f4f2e",
      "comment": "",
      "command": "click",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "b248c7ba-3895-405f-a781-acb3bc69f8f4",
      "comment": "",
      "command": "click",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "aab36340-9c15-4502-93a8-7332770cdd6a",
      "comment": "",
      "command": "doubleClick",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }]
  }, {
    "id": "f4bcc76a-b721-4907-a59f-8c9553af7345",
    "name": "14-Logeo de usuario registrado exitosamente.",
    "commands": [{
      "id": "67ce4e58-50fb-436b-aac0-e1953cc1e21f",
      "comment": "",
      "command": "open",
      "target": "/auth/sign-in",
      "targets": [],
      "value": ""
    }, {
      "id": "261c953b-30f9-4c96-aab3-fa506ec322aa",
      "comment": "",
      "command": "setWindowSize",
      "target": "1366x728",
      "targets": [],
      "value": ""
    }, {
      "id": "5bb450c9-c55f-426d-8ebb-bf3675c6e80d",
      "comment": "",
      "command": "click",
      "target": "id=email",
      "targets": [
        ["id=email", "id"],
        ["css=#email", "css:finder"],
        ["xpath=//input[@id='email']", "xpath:attributes"],
        ["xpath=//input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "a4f1fdd8-b8fa-4b22-a920-a70e0db21ced",
      "comment": "",
      "command": "type",
      "target": "id=email",
      "targets": [
        ["id=email", "id"],
        ["css=#email", "css:finder"],
        ["xpath=//input[@id='email']", "xpath:attributes"],
        ["xpath=//input", "xpath:position"]
      ],
      "value": "Ygarcia@gmail.com"
    }, {
      "id": "7cbe90d1-a0f5-4e08-976d-17c89621e4c3",
      "comment": "",
      "command": "click",
      "target": "css=.w-full > #password",
      "targets": [
        ["css=.w-full > #password", "css:finder"],
        ["xpath=//input[@id='password']", "xpath:attributes"],
        ["xpath=//app-password[@id='password']/div/input", "xpath:idRelative"],
        ["xpath=//app-password/div/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "ae4a1c3a-19c6-4286-84e5-da550c27dba3",
      "comment": "",
      "command": "type",
      "target": "css=.w-full > #password",
      "targets": [
        ["css=.w-full > #password", "css:finder"],
        ["xpath=//input[@id='password']", "xpath:attributes"],
        ["xpath=//app-password[@id='password']/div/input", "xpath:idRelative"],
        ["xpath=//app-password/div/input", "xpath:position"]
      ],
      "value": "Ygarcia2024+"
    }, {
      "id": "5c3a3910-ce5d-47cb-8806-c49a5c4d0d9e",
      "comment": "",
      "command": "click",
      "target": "css=.btn:nth-child(3)",
      "targets": [
        ["css=.btn:nth-child(3)", "css:finder"],
        ["xpath=//button[@type='submit']", "xpath:attributes"],
        ["xpath=//form/button", "xpath:position"]
      ],
      "value": ""
    }]
  }, {
    "id": "4f56c1aa-1ae9-48c4-af1d-a8eca6a7f23a",
    "name": "15-Logeo de usuario con correo inválido.",
    "commands": [{
      "id": "da37b29f-4402-4dfa-80d3-b2200fcbbe56",
      "comment": "",
      "command": "open",
      "target": "/auth/sign-in",
      "targets": [],
      "value": ""
    }, {
      "id": "3911a0bb-45a8-4711-8e52-0e14e727b818",
      "comment": "",
      "command": "setWindowSize",
      "target": "1366x728",
      "targets": [],
      "value": ""
    }, {
      "id": "11b66825-9dc3-48a1-9e2b-9889b1cebf2c",
      "comment": "",
      "command": "click",
      "target": "id=email",
      "targets": [
        ["id=email", "id"],
        ["css=#email", "css:finder"],
        ["xpath=//input[@id='email']", "xpath:attributes"],
        ["xpath=//input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "f5c55ff4-5295-40c4-859f-ddcc48066c97",
      "comment": "",
      "command": "type",
      "target": "id=email",
      "targets": [
        ["id=email", "id"],
        ["css=#email", "css:finder"],
        ["xpath=//input[@id='email']", "xpath:attributes"],
        ["xpath=//input", "xpath:position"]
      ],
      "value": "Ygarcia@gmail.com"
    }, {
      "id": "7b8cf432-7ff9-42cf-92ec-c8f8d8bcba47",
      "comment": "",
      "command": "click",
      "target": "id=email",
      "targets": [
        ["id=email", "id"],
        ["css=#email", "css:finder"],
        ["xpath=//input[@id='email']", "xpath:attributes"],
        ["xpath=//input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "66d5e16e-d332-4445-b64d-0e2272ab2a75",
      "comment": "",
      "command": "type",
      "target": "id=email",
      "targets": [
        ["id=email", "id"],
        ["css=#email", "css:finder"],
        ["xpath=//input[@id='email']", "xpath:attributes"],
        ["xpath=//input", "xpath:position"]
      ],
      "value": "Ygarcia1@gmail.com"
    }, {
      "id": "589da699-3d59-4524-8e75-8342b14f73b0",
      "comment": "",
      "command": "click",
      "target": "css=.w-full > #password",
      "targets": [
        ["css=.w-full > #password", "css:finder"],
        ["xpath=//input[@id='password']", "xpath:attributes"],
        ["xpath=//app-password[@id='password']/div/input", "xpath:idRelative"],
        ["xpath=//app-password/div/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "f7cee772-b3e3-47ee-a7d6-ba943ef1f962",
      "comment": "",
      "command": "type",
      "target": "css=.w-full > #password",
      "targets": [
        ["css=.w-full > #password", "css:finder"],
        ["xpath=//input[@id='password']", "xpath:attributes"],
        ["xpath=//app-password[@id='password']/div/input", "xpath:idRelative"],
        ["xpath=//app-password/div/input", "xpath:position"]
      ],
      "value": "Ygarcia2024+"
    }, {
      "id": "57567073-ac67-42c8-947e-0104780d4d09",
      "comment": "",
      "command": "click",
      "target": "css=.btn:nth-child(3)",
      "targets": [
        ["css=.btn:nth-child(3)", "css:finder"],
        ["xpath=//button[@type='submit']", "xpath:attributes"],
        ["xpath=//form/button", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "a90a40af-5561-4bdf-94f1-de03e02bff35",
      "comment": "Muestra msj de logeo incorrecto",
      "command": "assertText",
      "target": "css=.ml-3",
      "targets": [
        ["css=.ml-3", "css:finder"],
        ["xpath=//div/div[2]", "xpath:position"]
      ],
      "value": "User not found"
    }]
  }, {
    "id": "b8f3a5a8-a605-4c19-ae58-c70617ee0e64",
    "name": "16-Logeo de usuario con contraseña inválida.",
    "commands": [{
      "id": "f21d1efa-27c8-4946-889c-14d9a23182b4",
      "comment": "",
      "command": "open",
      "target": "/auth/sign-in",
      "targets": [],
      "value": ""
    }, {
      "id": "2eda2720-08c8-4bf2-ae4c-83082a841bbe",
      "comment": "",
      "command": "setWindowSize",
      "target": "1382x744",
      "targets": [],
      "value": ""
    }, {
      "id": "31635c2e-d4ba-42d8-9392-a8e4466b0142",
      "comment": "",
      "command": "click",
      "target": "id=email",
      "targets": [
        ["id=email", "id"],
        ["css=#email", "css:finder"],
        ["xpath=//input[@id='email']", "xpath:attributes"],
        ["xpath=//input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "98f09063-a51f-4823-8a53-7c3e1fd0f623",
      "comment": "",
      "command": "type",
      "target": "id=email",
      "targets": [
        ["id=email", "id"],
        ["css=#email", "css:finder"],
        ["xpath=//input[@id='email']", "xpath:attributes"],
        ["xpath=//input", "xpath:position"]
      ],
      "value": "Ygarcia@gmail.com"
    }, {
      "id": "d849c1b6-575b-4f79-9c96-d2373d9cd827",
      "comment": "",
      "command": "click",
      "target": "css=.w-full > #password",
      "targets": [
        ["css=.w-full > #password", "css:finder"],
        ["xpath=//input[@id='password']", "xpath:attributes"],
        ["xpath=//app-password[@id='password']/div/input", "xpath:idRelative"],
        ["xpath=//app-password/div/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "a8a38f68-8703-402c-b2fc-a3c7e1882e22",
      "comment": "",
      "command": "type",
      "target": "css=.w-full > #password",
      "targets": [
        ["css=.w-full > #password", "css:finder"],
        ["xpath=//input[@id='password']", "xpath:attributes"],
        ["xpath=//app-password[@id='password']/div/input", "xpath:idRelative"],
        ["xpath=//app-password/div/input", "xpath:position"]
      ],
      "value": "Ygarcia2024++"
    }, {
      "id": "8a475581-4bd8-49c5-baef-0673188d9cc3",
      "comment": "",
      "command": "click",
      "target": "css=.fa-solid",
      "targets": [
        ["css=.fa-solid", "css:finder"],
        ["xpath=//app-password[@id='password']/div/button/i", "xpath:idRelative"],
        ["xpath=//i", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "c31a4d6f-7de2-479d-9c90-49eb32d2d7c6",
      "comment": "",
      "command": "click",
      "target": "css=.btn:nth-child(3)",
      "targets": [
        ["css=.btn:nth-child(3)", "css:finder"],
        ["xpath=//button[@type='submit']", "xpath:attributes"],
        ["xpath=//form/button", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "713d6920-d284-416a-9d6c-28f22dd0fff8",
      "comment": "",
      "command": "click",
      "target": "css=.btn:nth-child(3)",
      "targets": [
        ["css=.btn:nth-child(3)", "css:finder"],
        ["xpath=//button[@type='submit']", "xpath:attributes"],
        ["xpath=//form/button", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "9d079308-8837-4b46-9cc5-cb0cb266cd07",
      "comment": "",
      "command": "click",
      "target": "css=.btn:nth-child(3)",
      "targets": [
        ["css=.btn:nth-child(3)", "css:finder"],
        ["xpath=//button[@type='submit']", "xpath:attributes"],
        ["xpath=//form/button", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "7daaa0a0-1273-44e6-aca2-3e2f6663f478",
      "comment": "",
      "command": "doubleClick",
      "target": "css=.btn:nth-child(3)",
      "targets": [
        ["css=.btn:nth-child(3)", "css:finder"],
        ["xpath=//button[@type='submit']", "xpath:attributes"],
        ["xpath=//form/button", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "ac5f4b95-de0c-4d66-9037-d60fdde2b020",
      "comment": "Msj de contraseña incorrecta",
      "command": "assertText",
      "target": "css=app-toast:nth-child(1) .ml-3",
      "targets": [
        ["css=app-toast:nth-child(1) .ml-3", "css:finder"],
        ["xpath=//div/div[2]", "xpath:position"]
      ],
      "value": "Password doesn't match"
    }]
  }, {
    "id": "7d609b1a-6462-4d80-9f3a-bdc978f15e2e",
    "name": "13-Logeo con datos faltantes (Sin contraseña)",
    "commands": [{
      "id": "2b2ae012-b5a1-454f-bbdb-c3f32ffc61a2",
      "comment": "",
      "command": "open",
      "target": "/auth/sign-in",
      "targets": [],
      "value": ""
    }, {
      "id": "bc1b3b5e-999a-4728-a440-9a42fb29a2dd",
      "comment": "",
      "command": "setWindowSize",
      "target": "1382x744",
      "targets": [],
      "value": ""
    }, {
      "id": "8aec8822-518f-464f-8595-1565c61a8298",
      "comment": "",
      "command": "click",
      "target": "id=email",
      "targets": [
        ["id=email", "id"],
        ["css=#email", "css:finder"],
        ["xpath=//input[@id='email']", "xpath:attributes"],
        ["xpath=//input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "b796b7ca-18cb-4543-8536-e479b64002dd",
      "comment": "",
      "command": "type",
      "target": "id=email",
      "targets": [
        ["id=email", "id"],
        ["css=#email", "css:finder"],
        ["xpath=//input[@id='email']", "xpath:attributes"],
        ["xpath=//input", "xpath:position"]
      ],
      "value": "Ygarcia@gmail.com"
    }, {
      "id": "41bce9e4-8430-4c40-b1b8-52485b3669ca",
      "comment": "",
      "command": "click",
      "target": "css=.flex:nth-child(2)",
      "targets": [
        ["css=.flex:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "8c59d7d7-d801-44c1-9b5c-30d54a0b7655",
      "comment": "",
      "command": "click",
      "target": "css=.flex:nth-child(2)",
      "targets": [
        ["css=.flex:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "8c56d1c0-8dca-4d3d-b5c1-0e6408045feb",
      "comment": "",
      "command": "click",
      "target": "css=.flex:nth-child(2)",
      "targets": [
        ["css=.flex:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }]
  }, {
    "id": "3c5d15a4-0bca-473a-a298-fd6c6eb821ba",
    "name": "17-Logeo con datos faltantes (Sin correo)",
    "commands": [{
      "id": "d8d25f10-def0-42ee-b5c3-7f825d8ea81b",
      "comment": "",
      "command": "open",
      "target": "/auth/sign-in",
      "targets": [],
      "value": ""
    }, {
      "id": "288cf57f-1ede-43de-8329-aa2d32be44dd",
      "comment": "",
      "command": "setWindowSize",
      "target": "1382x744",
      "targets": [],
      "value": ""
    }, {
      "id": "4540f969-1fb0-4bda-a93a-e3943a300533",
      "comment": "",
      "command": "click",
      "target": "css=.w-full > #password",
      "targets": [
        ["css=.w-full > #password", "css:finder"],
        ["xpath=//input[@id='password']", "xpath:attributes"],
        ["xpath=//app-password[@id='password']/div/input", "xpath:idRelative"],
        ["xpath=//app-password/div/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "2822a8a3-b722-4154-b20a-b2b3fc99f6a5",
      "comment": "",
      "command": "type",
      "target": "css=.w-full > #password",
      "targets": [
        ["css=.w-full > #password", "css:finder"],
        ["xpath=//input[@id='password']", "xpath:attributes"],
        ["xpath=//app-password[@id='password']/div/input", "xpath:idRelative"],
        ["xpath=//app-password/div/input", "xpath:position"]
      ],
      "value": "Ygarcia2024+"
    }, {
      "id": "db601da9-db80-4e8b-bc14-8b488c7b9591",
      "comment": "",
      "command": "click",
      "target": "css=.flex:nth-child(2)",
      "targets": [
        ["css=.flex:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "2897cfd4-6428-4c6b-b757-ce418d1f209a",
      "comment": "",
      "command": "click",
      "target": "css=.flex:nth-child(2)",
      "targets": [
        ["css=.flex:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "9e5b3112-6115-415d-96cc-f5cb4a7eea5b",
      "comment": "",
      "command": "click",
      "target": "css=.flex:nth-child(2)",
      "targets": [
        ["css=.flex:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }]
  }, {
    "id": "9a86dc71-b9b6-476f-816a-0c5ee4a99c40",
    "name": "18-Cierre de sesión.",
    "commands": [{
      "id": "06220741-edc2-42e2-8188-c021871e1c50",
      "comment": "",
      "command": "open",
      "target": "https://test-qa.inlaze.com/panel",
      "targets": [],
      "value": ""
    }, {
      "id": "6f66be3c-d8d8-4b5f-967d-b168217728d0",
      "comment": "",
      "command": "setWindowSize",
      "target": "1382x744",
      "targets": [],
      "value": ""
    }, {
      "id": "29a60219-947d-4abb-8e68-ac665f9919fc",
      "comment": "",
      "command": "click",
      "target": "css=img",
      "targets": [
        ["css=img", "css:finder"],
        ["xpath=//img[@alt='Rengoku']", "xpath:img"],
        ["xpath=//img", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "5d469856-69fb-497b-8397-d00ecb53a21a",
      "comment": "",
      "command": "click",
      "target": "linkText=Logout",
      "targets": [
        ["linkText=Logout", "linkText"],
        ["css=li:nth-child(3) > a", "css:finder"],
        ["xpath=//a[contains(text(),'Logout')]", "xpath:link"],
        ["xpath=//li[3]/a", "xpath:position"],
        ["xpath=//a[contains(.,'Logout')]", "xpath:innerText"]
      ],
      "value": ""
    }]
  }, {
    "id": "cec9aa38-22d0-47b1-9bfa-5f6affbb35e1",
    "name": "6-Registro con contraseña sin caracteres especiales",
    "commands": [{
      "id": "a6be8a23-d65f-4dc5-8cf4-6b1171071c34",
      "comment": "",
      "command": "open",
      "target": "https://test-qa.inlaze.com/auth/sign-in",
      "targets": [],
      "value": ""
    }, {
      "id": "7a1cdc43-ff7f-423d-80e1-74b098f93393",
      "comment": "",
      "command": "setWindowSize",
      "target": "1382x744",
      "targets": [],
      "value": ""
    }, {
      "id": "a5e9f510-c13b-4938-86d5-9a12ef43fbc0",
      "comment": "",
      "command": "click",
      "target": "linkText=Sign up",
      "targets": [
        ["linkText=Sign up", "linkText"],
        ["css=.text-primary", "css:finder"],
        ["xpath=//a[contains(text(),'Sign up')]", "xpath:link"],
        ["xpath=//a[contains(@href, '/auth/sign-up')]", "xpath:href"],
        ["xpath=//a", "xpath:position"],
        ["xpath=//a[contains(.,'Sign up')]", "xpath:innerText"]
      ],
      "value": ""
    }, {
      "id": "2dd1f50e-28ab-4e1e-a8e6-d2ff8bc2dd31",
      "comment": "",
      "command": "click",
      "target": "id=full-name",
      "targets": [
        ["id=full-name", "id"],
        ["css=#full-name", "css:finder"],
        ["xpath=//input[@id='full-name']", "xpath:attributes"],
        ["xpath=//input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "652b750b-85db-4146-b206-d6b9764c76cf",
      "comment": "",
      "command": "click",
      "target": "id=full-name",
      "targets": [
        ["id=full-name", "id"],
        ["css=#full-name", "css:finder"],
        ["xpath=//input[@id='full-name']", "xpath:attributes"],
        ["xpath=//input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "9328d424-4634-477f-b6c5-b6ef6c305498",
      "comment": "",
      "command": "type",
      "target": "id=full-name",
      "targets": [
        ["id=full-name", "id"],
        ["css=#full-name", "css:finder"],
        ["xpath=//input[@id='full-name']", "xpath:attributes"],
        ["xpath=//input", "xpath:position"]
      ],
      "value": "Nino Gonza"
    }, {
      "id": "a6792eb3-da8e-4dc1-b246-60d64013ad6d",
      "comment": "",
      "command": "click",
      "target": "id=email",
      "targets": [
        ["id=email", "id"],
        ["css=#email", "css:finder"],
        ["xpath=//input[@id='email']", "xpath:attributes"],
        ["xpath=//div[2]/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "e854f467-5ca0-4e98-b368-fd2785e27d56",
      "comment": "",
      "command": "mouseDownAt",
      "target": "id=email",
      "targets": [
        ["id=email", "id"],
        ["css=#email", "css:finder"],
        ["xpath=//input[@id='email']", "xpath:attributes"],
        ["xpath=//div[2]/input", "xpath:position"]
      ],
      "value": "13.821044921875,15.03125"
    }, {
      "id": "d529312d-1bb6-4c16-8852-fa9016c84327",
      "comment": "",
      "command": "mouseMoveAt",
      "target": "id=email",
      "targets": [
        ["id=email", "id"],
        ["css=#email", "css:finder"],
        ["xpath=//input[@id='email']", "xpath:attributes"],
        ["xpath=//div[2]/input", "xpath:position"]
      ],
      "value": "13.821044921875,15.03125"
    }, {
      "id": "1f4dd746-63b3-4a21-bca4-db79acd16564",
      "comment": "",
      "command": "mouseUpAt",
      "target": "id=email",
      "targets": [
        ["id=email", "id"],
        ["css=#email", "css:finder"],
        ["xpath=//input[@id='email']", "xpath:attributes"],
        ["xpath=//div[2]/input", "xpath:position"]
      ],
      "value": "13.821044921875,15.03125"
    }, {
      "id": "88ec5f8b-5dfa-474a-8543-2a45a4236cc6",
      "comment": "",
      "command": "click",
      "target": "id=email",
      "targets": [
        ["id=email", "id"],
        ["css=#email", "css:finder"],
        ["xpath=//input[@id='email']", "xpath:attributes"],
        ["xpath=//div[2]/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "ff9fd17e-19aa-437c-890c-e8a70e9660f5",
      "comment": "",
      "command": "click",
      "target": "css=.w-full > #password",
      "targets": [
        ["css=.w-full > #password", "css:finder"],
        ["xpath=//input[@id='password']", "xpath:attributes"],
        ["xpath=//app-password[@id='password']/div/input", "xpath:idRelative"],
        ["xpath=//app-password/div/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "33232822-3045-4a3b-9139-443790c0f5c1",
      "comment": "",
      "command": "type",
      "target": "css=.w-full > #password",
      "targets": [
        ["css=.w-full > #password", "css:finder"],
        ["xpath=//input[@id='password']", "xpath:attributes"],
        ["xpath=//app-password[@id='password']/div/input", "xpath:idRelative"],
        ["xpath=//app-password/div/input", "xpath:position"]
      ],
      "value": "Ngon20241"
    }, {
      "id": "17ebdec2-9a46-4254-aa94-4d4d43197a7c",
      "comment": "",
      "command": "click",
      "target": "css=.w-full > #confirm-password",
      "targets": [
        ["css=.w-full > #confirm-password", "css:finder"],
        ["xpath=//input[@id='confirm-password']", "xpath:attributes"],
        ["xpath=//app-password[@id='confirm-password']/div/input", "xpath:idRelative"],
        ["xpath=//div[4]/app-password/div/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "12f72b34-0041-4044-87cc-13cfba134c52",
      "comment": "",
      "command": "type",
      "target": "css=.w-full > #confirm-password",
      "targets": [
        ["css=.w-full > #confirm-password", "css:finder"],
        ["xpath=//input[@id='confirm-password']", "xpath:attributes"],
        ["xpath=//app-password[@id='confirm-password']/div/input", "xpath:idRelative"],
        ["xpath=//div[4]/app-password/div/input", "xpath:position"]
      ],
      "value": "Ngon20241"
    }, {
      "id": "baa9a9c1-aba5-4c86-aaed-ff8bf4af08d6",
      "comment": "",
      "command": "click",
      "target": "id=email",
      "targets": [
        ["id=email", "id"],
        ["css=#email", "css:finder"],
        ["xpath=//input[@id='email']", "xpath:attributes"],
        ["xpath=//div[2]/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "cdc618ef-4b9b-461a-abfb-296a94fab936",
      "comment": "",
      "command": "type",
      "target": "id=email",
      "targets": [
        ["id=email", "id"],
        ["css=#email", "css:finder"],
        ["xpath=//input[@id='email']", "xpath:attributes"],
        ["xpath=//div[2]/input", "xpath:position"]
      ],
      "value": "Ngonza@gmail.com"
    }, {
      "id": "d571bb2d-725c-40cc-b2d1-b2663de583a1",
      "comment": "",
      "command": "click",
      "target": "css=.btn:nth-child(5)",
      "targets": [
        ["css=.btn:nth-child(5)", "css:finder"],
        ["xpath=//button[@type='submit']", "xpath:attributes"],
        ["xpath=//form/button", "xpath:position"]
      ],
      "value": ""
    }]
  }, {
    "id": "7ee12e17-0c0e-4d2e-a569-0d0568fe882d",
    "name": "7-Registro de usuario con contraseña menor a 8 dígitos",
    "commands": [{
      "id": "1035263d-25c1-485f-9e1a-eecf43c8f12a",
      "comment": "",
      "command": "open",
      "target": "https://test-qa.inlaze.com/auth/sign-in",
      "targets": [],
      "value": ""
    }, {
      "id": "5ac0eed1-0519-4121-a11c-7bbc36b10cdd",
      "comment": "",
      "command": "setWindowSize",
      "target": "1382x744",
      "targets": [],
      "value": ""
    }, {
      "id": "a8a3ef6f-3063-4f91-a23c-a39a2cc7fe54",
      "comment": "",
      "command": "click",
      "target": "linkText=Sign up",
      "targets": [
        ["linkText=Sign up", "linkText"],
        ["css=.text-primary", "css:finder"],
        ["xpath=//a[contains(text(),'Sign up')]", "xpath:link"],
        ["xpath=//a[contains(@href, '/auth/sign-up')]", "xpath:href"],
        ["xpath=//a", "xpath:position"],
        ["xpath=//a[contains(.,'Sign up')]", "xpath:innerText"]
      ],
      "value": ""
    }, {
      "id": "60788df9-4091-44c4-9020-3bedc9648826",
      "comment": "",
      "command": "click",
      "target": "id=full-name",
      "targets": [
        ["id=full-name", "id"],
        ["css=#full-name", "css:finder"],
        ["xpath=//input[@id='full-name']", "xpath:attributes"],
        ["xpath=//input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "19538df1-8f2d-4f62-81d5-f30726c2aaa0",
      "comment": "",
      "command": "type",
      "target": "id=full-name",
      "targets": [
        ["id=full-name", "id"],
        ["css=#full-name", "css:finder"],
        ["xpath=//input[@id='full-name']", "xpath:attributes"],
        ["xpath=//input", "xpath:position"]
      ],
      "value": "Vivi Suarez"
    }, {
      "id": "9c60b556-499e-4e94-94e4-a970703589e1",
      "comment": "",
      "command": "click",
      "target": "id=email",
      "targets": [
        ["id=email", "id"],
        ["css=#email", "css:finder"],
        ["xpath=//input[@id='email']", "xpath:attributes"],
        ["xpath=//div[2]/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "2afc4722-7925-410f-b2b6-7a7f98576b63",
      "comment": "",
      "command": "type",
      "target": "id=email",
      "targets": [
        ["id=email", "id"],
        ["css=#email", "css:finder"],
        ["xpath=//input[@id='email']", "xpath:attributes"],
        ["xpath=//div[2]/input", "xpath:position"]
      ],
      "value": "Vsuarez@gmail.com"
    }, {
      "id": "abfa6a99-b528-49e0-8f57-323bbe201683",
      "comment": "",
      "command": "click",
      "target": "css=.w-full > #password",
      "targets": [
        ["css=.w-full > #password", "css:finder"],
        ["xpath=//input[@id='password']", "xpath:attributes"],
        ["xpath=//app-password[@id='password']/div/input", "xpath:idRelative"],
        ["xpath=//app-password/div/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "76043721-64a8-40e6-b7c7-fa6fa45f417a",
      "comment": "",
      "command": "type",
      "target": "css=.w-full > #password",
      "targets": [
        ["css=.w-full > #password", "css:finder"],
        ["xpath=//input[@id='password']", "xpath:attributes"],
        ["xpath=//app-password[@id='password']/div/input", "xpath:idRelative"],
        ["xpath=//app-password/div/input", "xpath:position"]
      ],
      "value": "Vsua2024"
    }, {
      "id": "24f93550-3cdd-480d-9dc8-809eeee97742",
      "comment": "",
      "command": "click",
      "target": "css=#password .btn",
      "targets": [
        ["css=#password .btn", "css:finder"],
        ["xpath=//button[@type='button']", "xpath:attributes"],
        ["xpath=//app-password[@id='password']/div/button", "xpath:idRelative"],
        ["xpath=//button", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "363d5021-f9d7-4772-9e04-40cf92f08127",
      "comment": "",
      "command": "click",
      "target": "css=.w-full > #password",
      "targets": [
        ["css=.w-full > #password", "css:finder"],
        ["xpath=//input[@id='password']", "xpath:attributes"],
        ["xpath=//app-password[@id='password']/div/input", "xpath:idRelative"],
        ["xpath=//app-password/div/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "a734315c-189d-4cae-8630-1b5ea6fd899b",
      "comment": "",
      "command": "click",
      "target": "css=.w-full > #password",
      "targets": [
        ["css=.w-full > #password", "css:finder"],
        ["xpath=//input[@id='password']", "xpath:attributes"],
        ["xpath=//app-password[@id='password']/div/input", "xpath:idRelative"],
        ["xpath=//app-password/div/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "0a64d7c9-2343-4c60-8955-066d39af7bb3",
      "comment": "",
      "command": "click",
      "target": "css=.w-full > #password",
      "targets": [
        ["css=.w-full > #password", "css:finder"],
        ["xpath=//input[@id='password']", "xpath:attributes"],
        ["xpath=//app-password[@id='password']/div/input", "xpath:idRelative"],
        ["xpath=//app-password/div/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "5c0d967e-afcc-4f6b-a4a2-ed25b67b6df8",
      "comment": "",
      "command": "click",
      "target": "css=.w-full > #password",
      "targets": [
        ["css=.w-full > #password", "css:finder"],
        ["xpath=//input[@id='password']", "xpath:attributes"],
        ["xpath=//app-password[@id='password']/div/input", "xpath:idRelative"],
        ["xpath=//app-password/div/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "9a338267-4d7a-4e87-a0a4-222c9d910640",
      "comment": "",
      "command": "click",
      "target": "css=.w-full > #password",
      "targets": [
        ["css=.w-full > #password", "css:finder"],
        ["xpath=//input[@id='password']", "xpath:attributes"],
        ["xpath=//app-password[@id='password']/div/input", "xpath:idRelative"],
        ["xpath=//app-password/div/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "316545e0-3aab-4dad-8317-a753ac981aee",
      "comment": "",
      "command": "type",
      "target": "css=.w-full > #password",
      "targets": [
        ["css=.w-full > #password", "css:finder"],
        ["xpath=//input[@id='password']", "xpath:attributes"],
        ["xpath=//app-password[@id='password']/div/input", "xpath:idRelative"],
        ["xpath=//app-password/div/input", "xpath:position"]
      ],
      "value": "Vsua202"
    }, {
      "id": "b21053a6-36a2-498c-9477-8c01e7e87e9b",
      "comment": "",
      "command": "click",
      "target": "css=.w-full > #confirm-password",
      "targets": [
        ["css=.w-full > #confirm-password", "css:finder"],
        ["xpath=//input[@id='confirm-password']", "xpath:attributes"],
        ["xpath=//app-password[@id='confirm-password']/div/input", "xpath:idRelative"],
        ["xpath=//div[4]/app-password/div/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "3385e56c-080b-4f78-9253-92417fc764c0",
      "comment": "",
      "command": "type",
      "target": "css=.w-full > #confirm-password",
      "targets": [
        ["css=.w-full > #confirm-password", "css:finder"],
        ["xpath=//input[@id='confirm-password']", "xpath:attributes"],
        ["xpath=//app-password[@id='confirm-password']/div/input", "xpath:idRelative"],
        ["xpath=//div[4]/app-password/div/input", "xpath:position"]
      ],
      "value": "Vsua202"
    }, {
      "id": "6b7dcb38-b72a-4d94-b9d9-017621b385de",
      "comment": "",
      "command": "click",
      "target": "css=#confirm-password .btn",
      "targets": [
        ["css=#confirm-password .btn", "css:finder"],
        ["xpath=(//button[@type='button'])[2]", "xpath:attributes"],
        ["xpath=//app-password[@id='confirm-password']/div/button", "xpath:idRelative"],
        ["xpath=//div[4]/app-password/div/button", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "758884a9-102d-42a7-9f1b-50ecd5e61ccb",
      "comment": "",
      "command": "click",
      "target": "css=.btn:nth-child(5)",
      "targets": [
        ["css=.btn:nth-child(5)", "css:finder"],
        ["xpath=//button[@type='submit']", "xpath:attributes"],
        ["xpath=//form/button", "xpath:position"]
      ],
      "value": ""
    }]
  }, {
    "id": "49cae7fe-4b66-4bfc-ac83-6518a93b112b",
    "name": "8-Registro de usuario con contraseña sin mayúsculas",
    "commands": [{
      "id": "c4f6696b-3974-48e3-8ad3-dd8a387fbc85",
      "comment": "",
      "command": "open",
      "target": "https://test-qa.inlaze.com/auth/sign-in",
      "targets": [],
      "value": ""
    }, {
      "id": "6548deac-2254-4f2f-ba31-176520d76289",
      "comment": "",
      "command": "setWindowSize",
      "target": "1382x744",
      "targets": [],
      "value": ""
    }, {
      "id": "b6370cbf-4d43-4b90-940a-e20961b59657",
      "comment": "",
      "command": "click",
      "target": "linkText=Sign up",
      "targets": [
        ["linkText=Sign up", "linkText"],
        ["css=.text-primary", "css:finder"],
        ["xpath=//a[contains(text(),'Sign up')]", "xpath:link"],
        ["xpath=//a[contains(@href, '/auth/sign-up')]", "xpath:href"],
        ["xpath=//a", "xpath:position"],
        ["xpath=//a[contains(.,'Sign up')]", "xpath:innerText"]
      ],
      "value": ""
    }, {
      "id": "d891495f-0f32-4766-a631-a9c922ee9b13",
      "comment": "",
      "command": "click",
      "target": "id=full-name",
      "targets": [
        ["id=full-name", "id"],
        ["css=#full-name", "css:finder"],
        ["xpath=//input[@id='full-name']", "xpath:attributes"],
        ["xpath=//input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "67093f4f-f0a7-4bc9-bd86-cecc3852fa92",
      "comment": "",
      "command": "type",
      "target": "id=full-name",
      "targets": [
        ["id=full-name", "id"],
        ["css=#full-name", "css:finder"],
        ["xpath=//input[@id='full-name']", "xpath:attributes"],
        ["xpath=//input", "xpath:position"]
      ],
      "value": "Estela Armero"
    }, {
      "id": "7d8e522f-e40e-42d3-a3c7-c2a9b1877f97",
      "comment": "",
      "command": "click",
      "target": "id=email",
      "targets": [
        ["id=email", "id"],
        ["css=#email", "css:finder"],
        ["xpath=//input[@id='email']", "xpath:attributes"],
        ["xpath=//div[2]/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "8bfcb2b0-7a78-40cc-b509-b468ec1e3d13",
      "comment": "",
      "command": "type",
      "target": "id=email",
      "targets": [
        ["id=email", "id"],
        ["css=#email", "css:finder"],
        ["xpath=//input[@id='email']", "xpath:attributes"],
        ["xpath=//div[2]/input", "xpath:position"]
      ],
      "value": "earmero@gmail.com"
    }, {
      "id": "8f6232e7-50cf-40e0-8dce-c9841cd904a5",
      "comment": "",
      "command": "click",
      "target": "css=.w-full > #password",
      "targets": [
        ["css=.w-full > #password", "css:finder"],
        ["xpath=//input[@id='password']", "xpath:attributes"],
        ["xpath=//app-password[@id='password']/div/input", "xpath:idRelative"],
        ["xpath=//app-password/div/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "cb92f121-c6ff-45ad-96c6-b577de744b43",
      "comment": "",
      "command": "type",
      "target": "css=.w-full > #password",
      "targets": [
        ["css=.w-full > #password", "css:finder"],
        ["xpath=//input[@id='password']", "xpath:attributes"],
        ["xpath=//app-password[@id='password']/div/input", "xpath:idRelative"],
        ["xpath=//app-password/div/input", "xpath:position"]
      ],
      "value": "earmero2024"
    }, {
      "id": "abd0b9c8-67dc-4a31-9466-34148402406b",
      "comment": "",
      "command": "click",
      "target": "css=#password .fa-solid",
      "targets": [
        ["css=#password .fa-solid", "css:finder"],
        ["xpath=//app-password[@id='password']/div/button/i", "xpath:idRelative"],
        ["xpath=//i", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "677f8572-27f3-4aec-90e1-74ff9fe6d2b8",
      "comment": "",
      "command": "click",
      "target": "css=.justify-center",
      "targets": [
        ["css=.justify-center", "css:finder"],
        ["xpath=//section[2]", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "088f7278-7a95-4c39-8394-47dd54dcd342",
      "comment": "",
      "command": "click",
      "target": "css=.w-full > #confirm-password",
      "targets": [
        ["css=.w-full > #confirm-password", "css:finder"],
        ["xpath=//input[@id='confirm-password']", "xpath:attributes"],
        ["xpath=//app-password[@id='confirm-password']/div/input", "xpath:idRelative"],
        ["xpath=//div[4]/app-password/div/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "31b1c087-bc0d-42e3-946c-ba303001a5f5",
      "comment": "",
      "command": "type",
      "target": "css=.w-full > #confirm-password",
      "targets": [
        ["css=.w-full > #confirm-password", "css:finder"],
        ["xpath=//input[@id='confirm-password']", "xpath:attributes"],
        ["xpath=//app-password[@id='confirm-password']/div/input", "xpath:idRelative"],
        ["xpath=//div[4]/app-password/div/input", "xpath:position"]
      ],
      "value": "earmero2024"
    }, {
      "id": "90a78809-df5b-4c35-a078-4607b6f6d4e5",
      "comment": "",
      "command": "click",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "aeeb699f-67cc-4be5-a06b-a9b1113b3cac",
      "comment": "",
      "command": "click",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "61ef30ce-3b8f-4e76-805b-4fc758ddfded",
      "comment": "",
      "command": "click",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }]
  }, {
    "id": "401cd034-823f-4f61-a4d9-7c051c1d18fe",
    "name": "9-Registro de usuario sin minúsculas",
    "commands": [{
      "id": "3ac1e813-89b9-44c6-8aa2-6dcd7a66e09b",
      "comment": "",
      "command": "open",
      "target": "https://test-qa.inlaze.com/auth/sign-in",
      "targets": [],
      "value": ""
    }, {
      "id": "cd8e4ee5-d9a3-4edd-be58-25081baebee5",
      "comment": "",
      "command": "setWindowSize",
      "target": "1382x744",
      "targets": [],
      "value": ""
    }, {
      "id": "f34fdab9-4e9d-4c9d-bdf3-a441b0c60af4",
      "comment": "",
      "command": "click",
      "target": "linkText=Sign up",
      "targets": [
        ["linkText=Sign up", "linkText"],
        ["css=.text-primary", "css:finder"],
        ["xpath=//a[contains(text(),'Sign up')]", "xpath:link"],
        ["xpath=//a[contains(@href, '/auth/sign-up')]", "xpath:href"],
        ["xpath=//a", "xpath:position"],
        ["xpath=//a[contains(.,'Sign up')]", "xpath:innerText"]
      ],
      "value": ""
    }, {
      "id": "a0cca4dc-68ef-44a8-b3f7-fbec578b084a",
      "comment": "",
      "command": "click",
      "target": "id=full-name",
      "targets": [
        ["id=full-name", "id"],
        ["css=#full-name", "css:finder"],
        ["xpath=//input[@id='full-name']", "xpath:attributes"],
        ["xpath=//input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "e4fe73fe-9ad0-4fa3-9a66-886802304a05",
      "comment": "",
      "command": "type",
      "target": "id=full-name",
      "targets": [
        ["id=full-name", "id"],
        ["css=#full-name", "css:finder"],
        ["xpath=//input[@id='full-name']", "xpath:attributes"],
        ["xpath=//input", "xpath:position"]
      ],
      "value": "Nico Diaz"
    }, {
      "id": "945208fa-864d-484e-b57a-eea3afa15503",
      "comment": "",
      "command": "click",
      "target": "id=email",
      "targets": [
        ["id=email", "id"],
        ["css=#email", "css:finder"],
        ["xpath=//input[@id='email']", "xpath:attributes"],
        ["xpath=//div[2]/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "87ae1d4c-c57d-48db-b872-a492011848df",
      "comment": "",
      "command": "type",
      "target": "id=email",
      "targets": [
        ["id=email", "id"],
        ["css=#email", "css:finder"],
        ["xpath=//input[@id='email']", "xpath:attributes"],
        ["xpath=//div[2]/input", "xpath:position"]
      ],
      "value": "Ndiaz@gmail.com"
    }, {
      "id": "1920d47d-6962-4607-822a-d45a8183ac75",
      "comment": "",
      "command": "click",
      "target": "css=.w-full > #password",
      "targets": [
        ["css=.w-full > #password", "css:finder"],
        ["xpath=//input[@id='password']", "xpath:attributes"],
        ["xpath=//app-password[@id='password']/div/input", "xpath:idRelative"],
        ["xpath=//app-password/div/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "d9268af4-a23c-42ab-8fd5-1c215bbe790d",
      "comment": "",
      "command": "type",
      "target": "css=.w-full > #password",
      "targets": [
        ["css=.w-full > #password", "css:finder"],
        ["xpath=//input[@id='password']", "xpath:attributes"],
        ["xpath=//app-password[@id='password']/div/input", "xpath:idRelative"],
        ["xpath=//app-password/div/input", "xpath:position"]
      ],
      "value": "NDIAZ"
    }, {
      "id": "887d54dd-d92b-4196-82a9-d92721caf53b",
      "comment": "",
      "command": "click",
      "target": "css=#password .fa-solid",
      "targets": [
        ["css=#password .fa-solid", "css:finder"],
        ["xpath=//app-password[@id='password']/div/button/i", "xpath:idRelative"],
        ["xpath=//i", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "2840c5c6-5d1d-4971-b3a2-314fdcea00d7",
      "comment": "",
      "command": "click",
      "target": "css=.w-full > #password",
      "targets": [
        ["css=.w-full > #password", "css:finder"],
        ["xpath=//input[@id='password']", "xpath:attributes"],
        ["xpath=//app-password[@id='password']/div/input", "xpath:idRelative"],
        ["xpath=//app-password/div/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "145bb16c-6c94-4896-9b9f-ab84bdac101d",
      "comment": "",
      "command": "click",
      "target": "css=.justify-center",
      "targets": [
        ["css=.justify-center", "css:finder"],
        ["xpath=//section[2]", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "5796e8d2-d9a3-489c-bd49-cdc3d2403d18",
      "comment": "",
      "command": "type",
      "target": "css=.w-full > #password",
      "targets": [
        ["css=.w-full > #password", "css:finder"],
        ["xpath=//input[@id='password']", "xpath:attributes"],
        ["xpath=//app-password[@id='password']/div/input", "xpath:idRelative"],
        ["xpath=//app-password/div/input", "xpath:position"]
      ],
      "value": "NDIAZ2024+"
    }, {
      "id": "32ca7abb-14a8-42b0-bb9c-8095809f784e",
      "comment": "",
      "command": "click",
      "target": "css=.w-full > #confirm-password",
      "targets": [
        ["css=.w-full > #confirm-password", "css:finder"],
        ["xpath=//input[@id='confirm-password']", "xpath:attributes"],
        ["xpath=//app-password[@id='confirm-password']/div/input", "xpath:idRelative"],
        ["xpath=//div[4]/app-password/div/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "93751dfc-e6b6-44ce-874d-c19a5970adc0",
      "comment": "",
      "command": "type",
      "target": "css=.w-full > #confirm-password",
      "targets": [
        ["css=.w-full > #confirm-password", "css:finder"],
        ["xpath=//input[@id='confirm-password']", "xpath:attributes"],
        ["xpath=//app-password[@id='confirm-password']/div/input", "xpath:idRelative"],
        ["xpath=//div[4]/app-password/div/input", "xpath:position"]
      ],
      "value": "NDIAZ2024+"
    }, {
      "id": "faef450d-037e-4437-b19d-b020d02b1525",
      "comment": "",
      "command": "click",
      "target": "css=.w-full > #password",
      "targets": [
        ["css=.w-full > #password", "css:finder"],
        ["xpath=//input[@id='password']", "xpath:attributes"],
        ["xpath=//app-password[@id='password']/div/input", "xpath:idRelative"],
        ["xpath=//app-password/div/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "5cfaba39-6b97-4b01-b898-8aa7969644ae",
      "comment": "",
      "command": "click",
      "target": "css=.w-full > #password",
      "targets": [
        ["css=.w-full > #password", "css:finder"],
        ["xpath=//input[@id='password']", "xpath:attributes"],
        ["xpath=//app-password[@id='password']/div/input", "xpath:idRelative"],
        ["xpath=//app-password/div/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "14ef8a56-3f63-441b-b475-557fa88fa206",
      "comment": "",
      "command": "click",
      "target": "css=.w-full > #password",
      "targets": [
        ["css=.w-full > #password", "css:finder"],
        ["xpath=//input[@id='password']", "xpath:attributes"],
        ["xpath=//app-password[@id='password']/div/input", "xpath:idRelative"],
        ["xpath=//app-password/div/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "f24fdd4f-434a-4fcd-a765-25ec6e8b49cd",
      "comment": "",
      "command": "click",
      "target": "css=.w-full > #password",
      "targets": [
        ["css=.w-full > #password", "css:finder"],
        ["xpath=//input[@id='password']", "xpath:attributes"],
        ["xpath=//app-password[@id='password']/div/input", "xpath:idRelative"],
        ["xpath=//app-password/div/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "00895727-4553-4a6c-8b6c-d0b22cbc82fe",
      "comment": "",
      "command": "click",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "82da355b-0460-4d29-a6db-e4db2479ee2f",
      "comment": "",
      "command": "click",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "11d1d7c1-9494-45a5-9289-4e87d117357b",
      "comment": "",
      "command": "click",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "476ac0db-766f-4828-bc8a-675ad9013666",
      "comment": "",
      "command": "click",
      "target": "css=.flex-col:nth-child(2)",
      "targets": [
        ["css=.flex-col:nth-child(2)", "css:finder"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }]
  }],
  "suites": [],
  "urls": ["https://test-qa.inlaze.com/", "https://test-qa.inlaze.com/panel"],
  "plugins": []
}

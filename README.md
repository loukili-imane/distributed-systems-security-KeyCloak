# distributed-systems-security-KeyCloak

Partie 1
1. Télécharger Keycloak
   ![image](https://github.com/loukili-imane/distributed-systems-security-KeyCloak/assets/93887037/ab3c9d59-ca11-4812-ba83-8fb4fb243ff1)


3. Démarrer Keycloak
    ![image](https://github.com/loukili-imane/distributed-systems-security-KeyCloak/assets/93887037/9592317b-eef8-4158-a5e7-a4f0d226a679)

   ![image](https://github.com/loukili-imane/distributed-systems-security-KeyCloak/assets/93887037/4ae5275c-b83e-4f44-893d-a054efa0ca38)

5. Créer un compte Admin
![image](https://github.com/loukili-imane/distributed-systems-security-KeyCloak/assets/93887037/b84d38fa-861c-496b-84b9-11b2b9ac6b27)
![image](https://github.com/loukili-imane/distributed-systems-security-KeyCloak/assets/93887037/1caf1d07-22af-44b0-92cb-245baae39883)

7. Créer une Realm
   ![image](https://github.com/loukili-imane/distributed-systems-security-KeyCloak/assets/93887037/dc9f46a9-8228-489b-928f-5c98379d2dfb)
   ![image](https://github.com/loukili-imane/distributed-systems-security-KeyCloak/assets/93887037/51a7a3af-f9c7-42ab-979c-61e0544d1398)


9. Créer un client à sécuriser
   ![image](https://github.com/loukili-imane/distributed-systems-security-KeyCloak/assets/93887037/19b7d628-4884-4640-8ac3-9b4c236ec4f4)
   ![image](https://github.com/loukili-imane/distributed-systems-security-KeyCloak/assets/93887037/5afe93b1-ff8c-4455-b8e6-4ecf8bbcea21)
   ![image](https://github.com/loukili-imane/distributed-systems-security-KeyCloak/assets/93887037/fe8ee943-fe1e-4f26-a025-5c3bdd945ac6)
   ![image](https://github.com/loukili-imane/distributed-systems-security-KeyCloak/assets/93887037/28c10ce2-74b5-4d47-851a-0840f61e3dd6)


11. Créer des utilisateurs
    ![image](https://github.com/loukili-imane/distributed-systems-security-KeyCloak/assets/93887037/d8015807-a847-44e3-bbfc-2a8adf137cb9)

    ![image](https://github.com/loukili-imane/distributed-systems-security-KeyCloak/assets/93887037/5c3fca67-ce08-4139-a18b-ab35dc747128)
    ![image](https://github.com/loukili-imane/distributed-systems-security-KeyCloak/assets/93887037/4bdb6d08-2c6d-461c-9c71-6921e1422567)

    ![image](https://github.com/loukili-imane/distributed-systems-security-KeyCloak/assets/93887037/06d72d62-6cb0-4790-bbbc-9ffbeddeae53)
    ![image](https://github.com/loukili-imane/distributed-systems-security-KeyCloak/assets/93887037/51b65b17-0e40-45a0-86ba-a2bf4fbd5756)
    ![image](https://github.com/loukili-imane/distributed-systems-security-KeyCloak/assets/93887037/104c0da3-91e1-4a09-876e-dc304739d8d2)
    ![image](https://github.com/loukili-imane/distributed-systems-security-KeyCloak/assets/93887037/99ed2459-b093-4328-ad2d-19965d285b3f)


13. Créer des rôles
    ![image](https://github.com/loukili-imane/distributed-systems-security-KeyCloak/assets/93887037/893c89c3-4f68-4ebe-b804-3faedf0f7511)
![image](https://github.com/loukili-imane/distributed-systems-security-KeyCloak/assets/93887037/e61520d5-5199-49c8-849c-72c5bf138171)

15. Affecter les rôles aux utilisateurs
    ![image](https://github.com/loukili-imane/distributed-systems-security-KeyCloak/assets/93887037/dd4e1903-7dc7-43b7-99c5-bf3b9f8760b4)
![image](https://github.com/loukili-imane/distributed-systems-security-KeyCloak/assets/93887037/2f200424-38d3-49b1-81a8-29241e2e0a5b)
![image](https://github.com/loukili-imane/distributed-systems-security-KeyCloak/assets/93887037/390ab33d-fe30-4c8e-9461-4e8296dcc55e)
![image](https://github.com/loukili-imane/distributed-systems-security-KeyCloak/assets/93887037/46eb538b-819d-4ddb-97e3-49be02a839ea)

17. Avec PostMan :
    ![image](https://github.com/loukili-imane/distributed-systems-security-KeyCloak/assets/93887037/6f6cdc4f-2dbf-4586-92b4-79adf8113d81)
![image](https://github.com/loukili-imane/distributed-systems-security-KeyCloak/assets/93887037/08fa2275-7ba1-493d-ba99-cf6a9a037827)
![image](https://github.com/loukili-imane/distributed-systems-security-KeyCloak/assets/93887037/f5bb0ac9-1712-4473-8123-48652a8b5505)

    - Tester l'authentification avec le mot de passe
    ![image](https://github.com/loukili-imane/distributed-systems-security-KeyCloak/assets/93887037/f603946f-339f-4267-9908-fed232c9540e)
![image](https://github.com/loukili-imane/distributed-systems-security-KeyCloak/assets/93887037/e83f8a88-75d2-4377-93ff-17ba4587db66)

    - Analyser les contenus des deux JWT Access Token et Refresh Token
    - Tester l'authentification avec le Refresh Token
    - Tester l'authentification avec Client ID et Client Secret
    - Changer les paramètres des Tokens Access Token et Refresh Token

Partie  2 :
   -Sécuriser avec Keycloak les applications Products-App (Frontend avec thymeleaf) et Supplier-service (Micro-service backend) 

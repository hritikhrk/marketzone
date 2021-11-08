# MarketZone

> Frontend -> React JS

> Backend -> Node JS & Express JS

> Database -> MongoDB

## Installation process
1. #### clone the repo using this command
    ```bash
    git clone https://github.com/hritikhrk/marketzone.git
    ```
2. #### install npm packages
    1. install backend packages
    ```bash
    cd marketzone
    npm install
    ```
    1. install frontend packages
    ```bash
    cd client
    npm install
    ```
3. go to the parent folder of mern-ecommerce & create .env for connection, JWT_SECRET, BRAINTREE_MERCHANT_ID, BRAINTREE_PUBLIC_KEY and BRAINTREE_PRIVATE_KEY.

    ```bash
    cd marketzone
    sudo nano .env
    ```
    (ctrl+x to save & nano follow instruction there)
    
    ##### sample code for backend .env
    ```env
    MONGODB_URI=YOUR_MONGODB_URI
    JWT_SECRET=YOUR_JWT_SECRET
    BRAINTREE_MERCHANT_ID=YOUR_BRAINTREE_MERCHANT_ID
    BRAINTREE_PUBLIC_KEY=YOUR_BRAINTREE_PUBLIC_KEY
    BRAINTREE_PRIVATE_KEY=YOUR_BRAINTREE_PRIVATE_KEY
    ```
4.  create another .env file inside client directory for REACT_APP_API_URL.

    ```bash
    cd marketzone/client
    sudo nano .env
    ```
    ##### sample code for frontend .env
    ```env
    REACT_APP_API_URL=YOUR_API_URL
    ```
    1. #### note: add .env on .gitignore
    2. for server deployment use secrets directly

5. <b>deploy this project</b> on your local server by using this command
    ```bash
    cd marketzone
    npm run dev
    ```
    #### note: both backend & frontend server will start at once with the above command.

### App Description:
    1. user can view all products
    2. user can view single product
    3. user can search products and view products by category and price range
    4. user can add to cart checkout products using credit card info
    5. user can register & sign in
    6. admin can create, edit, update & delete products
    7. admin can create categories
    8. admin can view ordered products
    9. admin can change the status of a product (processing, shipped, delivered, etc.)

6. <b>Deployed on</br> https://marketzon.herokuapp.com/ 
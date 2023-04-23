# diapers_backend
this is the backend for the diapers it is using JSON Server internally for all the CRUD operations.

#URL endpoints for products
<h1> endpoint for getting product of specific category </h1> (GET)
--- <b>https://diapers-backnd.onrender.com/${category}</b>

<h1> endpoint for searching product of specific category </h1> (GET)
--- <b>https://diapers-backnd.onrender.com/?q=${query}</b>

<h1> endpoint for filtering product with high rating of specific category </h1> (GET)
--- <b>https://diapers-backnd.onrender.com/?rating_like=5</b>

<h1> endpoint for sorting the product prices of specific category </h1> (GET)
--- <b>https://diapers-backnd.onrender.com/?_sort=price&_order=${price}</b>

<h1> endpoint for getting the product details of specific product </h1> (GET)
--- <b>https://diapers-backnd.onrender.com/${category}/${id}</b>

#URL endpoints for cart data

<h1> endpoint for getting all cart data of specific user </h1> (GET)
--- <b>https://diapers-backnd.onrender.com/Cart?userId={id}</b>

<h1> endpoint for adding cart data of specific user </h1> (POST)
--- <b>https://diapers-backnd.onrender.com/Cart</b>

<h1> endpoint for deleting cart data of specific user </h1> (DELETE)
--- <b>https://diapers-backnd.onrender.com/Cart/?userId={id}&${id}</b>

<h1> endpoint for changing cart data of specific user </h1> (PATCH)
--- <b>https://diapers-backnd.onrender.com/Cart/?userId={id}&${id}</b>

#URL endpoints for Orders data

<h1> endpoint for getting all Orders data of specific user </h1> (GET)
--- <b>https://diapers-backnd.onrender.com/Orders?userId={id}</b>

<h1> endpoint for adding Orders data of specific user </h1> (POST)
--- <b>https://diapers-backnd.onrender.com/Orders</b>


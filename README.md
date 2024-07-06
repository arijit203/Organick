<h2>
Salient Features of the Grocery Application(Organick) :</h2>


<ul>
  <li>Developed a fully functional Multi-user Grocery Application for purchasing groceries.</li>
  <li>New users cannot register until all input fields are filled, and their email is verified using <strong>OTP</strong>. Username and Email should be unique for each user. Passwords must meet specific criteria, including alphabetic, numeric, and special characters, with a length between 8 to 32 characters.</li>
  <li>Implemented email verification using the <strong><em>Smtp.js</em></strong> API for user registration, sending <strong>OTP</strong> to the respective user email.</li>
  <li>For pre-existing users, login is possible using their email and password. If the password is forgotten, it can be updated after email verification through <strong>OTP</strong> sent by the <strong><em>Smtp.js</em></strong> API.</li>
  <li>Once registered or logged in, users can buy products/items from one or more categories, adding to the cart. They can also edit or delete the quantity of items in the cart before proceeding to checkout.</li>
  <li>The <strong>Search functionality</strong> accommodates users looking for relatively close category names, providing flexibility in searching for categories with similar or closely related names. This feature enhances user convenience by allowing for more tolerant and versatile search queries.</li>
  <li>Integrated <strong><em>Google API</em></strong> for real-time address suggestions and validation during user input for new or existing addresses.</li>
  <li>An email containing a <strong>Delivery Receipt</strong>, along with essential information, is sent to the user's email using the <strong><em>smtplib</em></strong> module along with the  <strong><em>email.message</em></strong> module to create the message.</li>
  <li>Seperate dashboard for Admin/Manager with capabilities that include adding/editing/deleting categories and products.</li>
  <li>Created a bar graph summary of category utilization and comparison of quantities of items bought using the Python <strong><em>Matplotlib</em></strong> library.</li>
</ul>

<h4>Teck Stack Used:</h4>
<ol>
  <li><strong>Frontend:</strong> HTML, Bootstrap, CSS and Javascript </li>
  <li>
    <strong>Control route functions:</strong> Flask was utilized to handle incoming HTTP requests on a specific port, implementing control route functions and redirecting to other routes as required.
  </li>
  <li>
    <strong>Asynchronous Communication:</strong> AJAX allows for asynchronous communication between a web browser and a web server. It enables the exchange of data with the server without reloading the entire page.
  </li>
  <li>
   <strong>External APIs Incorporated:</strong> Smtp.js, Google Javascript API
  </li>
  <li>
    <strong>Backend:</strong> SQLite Database was used for storing and fetching data for both Admin and Customers.
  </li>
  
</ol>



Video Link: https://drive.google.com/file/d/1Cb48oXbuQOw2GHJGyINJ_CQWAejURIEg/view?usp=sharing

<img width="1280" alt="Groc_pic1" src="https://github.com/arijit203/GROC/assets/99786400/9c47cf54-ceb1-4087-b98b-4009114204a9">

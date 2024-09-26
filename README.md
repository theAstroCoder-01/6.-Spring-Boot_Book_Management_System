# 6.-Spring-Boot_Book_Management_System

<!DOCTYPE html>
<html>

<body>

<h1>Spring-Boot_Book_Management_System</h1>

<p><strong>Book Management System</strong> is a REST API with CRUD operations that allows the user to Create, Read, Update, and Delete any kind of book. This API includes a MyBook section in the menu
  where the books of your preference are stored.
  
<h2>Index</h2>

<ol>
   <li><a href="#classes">Classes</a>
        <ul>
            <li><a href="#bookstoreapplication">BookStoreApplication</a></li>
            <li><a href="#book">Book</a></li>
            <li><a href="#mybooklist">MyBookList</a></li>
            <li><a href="#bookcontroller">BookController</a></li>
            <li><a href="#mybooklistcontroller">MyBookListController</a></li>
            <li><a href="#bookrepository">BookRepository</a></li>
            <li><a href="#mybookrepository">MyBookRepository</a></li>
            <li><a href="#bookservice">BookService</a></li>
            <li><a href="#mybooklistservice">MyBookListService</a></li>
        </ul>
    </li>
</ol>

<h2 id="classes">Classes</h2>

<h3 id="bookstoreapplication">AppLauncher</h3>
<p>The <code>BookStoreApplication</code> class contains the main method that runs the Spring Boot application.</p>

<h3 id="book">Book</h3>
<p>The <code>Book</code> class stores the data that maps to database tables. In this case the <code>Book</code> class corresponds to a table in MySQL, and its fields (id, firstName, lastName, email) correspond to the columns in that table. </p>

<h3 id="mybooklist">MyBookList</h3>
<p>The <code>MyBookList</code> class also stores the data that maps to the database table. </p>

<h3 id="bookcontroller">BookController</h3>
<p>The <code>bookcontroller</code> class will handles HTTP requests which define the endpoints of the API. Also, it uses service classes to perform business logic.

<h3 id="mybooklistcontroller">MyBookListController</h3>
<p>The <code>mybooklistcontroller</code>class includes the deleteMyList method, and after deleting books it returns the user to MyBooks section.

<h3 id="bookrepository">BookRepository</h3>
<p>The <code>bookrepository</code> interface extends JpaRepository and provides methods for CRUD operations inside the API REST.  

<h3 id="mybookrepository">MyBookRepository</h3>
<p>The <code>mybookrepository</code> interface extends JpaRepository and provides methods for CRUD operations inside the API REST.  

<h3 id="bookservice">BookService</h3>
<p>The <code>bookservice</code> interface extends JpaRepository and provides methods for CRUD operations inside the API REST. 
  
<h3 id="mybooklistservice">MyBookListService</h3>
<p>The <code>mybookservice</code> interface extends JpaRepository and provides methods for CRUD operations inside the API REST. 

</body>

</html>

![1](https://github.com/user-attachments/assets/4c8bdda3-d36f-4279-a26d-1db7f9b1655b)
![2](https://github.com/user-attachments/assets/9147af57-84a3-4f97-a197-f8951362f3d0)
![3](https://github.com/user-attachments/assets/8b6e9e44-f552-4197-95c3-192377a76082)

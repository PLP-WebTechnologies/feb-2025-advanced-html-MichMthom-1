<!--
    Document: index.html
    Description: Demonstrates
HTML5 features, including images,
tables, forms,
                    input types,
form validation, and multimedia
elements.
-->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewpoint"
 content="width=device-width,
 initial-scale=1.0">
      <title>HTML5 Demo</title>
      <style>
          /* Add some basic styling 
  */
          body {
               font-family: Arial,
   sans=serif;
           }
           table {
               border-collapses:
   collapse;
           }
           th, td {
               border: 1px solid
    #ddd; 
               padding:  10px;
            }
            th { 
                background-color:
    #f0f0f0;
            }
         </style>
</head>
<body>
    <!-- Ordered list with Roman
 numerals ==>
     <h2>Ordered List with Roman
 Numerals</h2>
     <ol type="I">
          <li>Item 1<li>
          <li>Item 2<li>
          <li>Item 3<li>
     </ol>

     <!-- External image from
 Pexels -->
     <h2>External Image</h2>
     <img src="https://images 
 .pexels.com/photos/1323554/pexels
 -photo-1323554.jpeg?auto=compress
 &CS=tinysrgb&dpr=2&h=750&w=
 1260" alt="Image from Pexels"
 width="500" height="300">

     <!-- Table with 5 contacts -->
     <h2>Contacts</h2>
     <table>
         <tr>
             <th>Name</th>
             <th>Address</th>
             <th>Mobile</th>
             <th>Email</th>
          </tr>
          <tr>
              >td>John Doe</td>
              <td>123 Main St,
     Anytown, USA</td>
                 <td>123-456-7890</td>
                 <td>johndoe@example
     .com</td>
             </tr>
             <tr>
                 <td>Jane Smith</td>
                 <td>456 Elm st,
     Othertown, USA</TD>
                 <td>987-654-3210<td>
                 <td>janesmith@example
      .com</td>
              </tr>
              <tr>
                   <td>Bob johnson</td>
                   <td>789 Oak St,
     Somewhere, USA</td>
                 <td>555-123-4567</td>
                 <td>bobjohnson@example
      .com</td>
              </tr>
              <tr>
                  <td>Alice Brown</td>
                  <td>321 Maple St,

      Anytown, USA</td>
                  <td>901-234-5678</td>
                  <td>alicebrown@example
      .com</td>
              </tr>
              <tr>
                   <td>Mike Davis</td>
                   <td>901 Pine St,
       Othertown, USA</td>
                   <td>111-222-3333</td>
                   <td>mikedavis@example
        .com</td>
                </tr>
               </table>

               <!-- Registration form -->
               <h2>Registration Form</h2>
               <form>
                   <label for="name">Name:</
           label>
                  <input type="text"
            id="name" name="name" required
            placeholder="Enter your name">
                    <br><br>
                    <label
             for="email">Email:</label>
                     <input type="email"
             id="email" name="email" required
             placeholder="Enter your email">
                     <br><br>
                     <label
             for="email">Email:</label>
                     <input type="email"
              id="email" name="email" required
              placeholder="Enter your email">
                      <br><br>
                      <label
              for="email">Email:</label>
                      <input type="email"
               id="email" name="email" required
               placeholder="Enter your email">
                       <br><br.
                       <label
                for="password">Password:</label>
                         <input type="password"
                id="password" name="password"
                required placeholder="Enter
                your password" pattern=".{8,}"
                title="Password must be at least 8
                characters'>
                        <br><br>
                        <label for="date">Date of 
                Birth:</label>
                         <input type="date"
                 id="date" name="date" required>
                          <br><br>
                          <label
                 for="country">Country:</label>
                         <select id="country"
                  name="country" required>
                              <option
                  value="">Select a country</option>
                                <option
                  value="USA">USA</option>
                                <option
                  value="Canada">Canada</option>
                              <option
                   value="Mexico">Mexico</option>
                           </select>
                           <br><br>
                           <label
                    for="gender">Gender:</label>
                            <input type="radio"
                    id="male" name="gender"
                    value="male" required>
                            <label for="male">Male</
                     label>
                            <input type="ratio"
                     id="female" name="gender"
                     value="female" required>

         

# Dinify-Assignment

## Business Understanding
Dinify is an instant ordering plus order management platform for restaurants and food trucks in Canada. Dinify.io works by providing restaurants and businesses with a cloud-based platform that allows them to manage their online ordering, tabletop ordering, and takeout ordering process. Some features of the platform are as follows:
<ul>
  <li>
    Menu management: Restaurants can easily add, remove, and update their menus on the Dinify.io platform. They can also set prices, create discounts, and mark menu items as offline.</li>
  <li>Order management: Restaurants can manage all of their incoming orders from one central location. They can view order details, accept or reject orders, and track the status of orders.</li>
  <li>Tabletop ordering: Dinify.io allows customers to place and pay for orders at their table using the restaurant's own tablets or their own smartphones. This helps to reduce the workload on servers and allows   customers to have a more contactless dining experience.</li>
  <li>Takeout ordering: Dinify.io allows customers to place and pay for takeout orders online. Customers can choose a pickup time and pay for their order using a variety of contactless payment methods.</li>
  <li>Send order notifications: Dinify.io can send customers text notifications when their order is ready or when their table is ready.</li>
  <li>Split bills: Dinify.io allows customers to split their bills at the table, making it easy for groups to dine together.</li>
  <li>Collect feedback: Dinify.io allows restaurants to collect feedback from customers about their experience. This feedback can be used to improve the restaurant's menu, service, and overall operations.</li>
</ul>

#### Practical Example:
<ul>
  <li>A customer arrives at a restaurant and scans a QR code on the table. This takes them to the restaurant's Dinify.io menu, where they can browse items and place an order.</li>
  <li>The customer's order is sent to the kitchen, where it is prepared. Once the order is ready, the kitchen staff notifies the customer using the Dinify.io platform.</li>
  <li>The customer can then pay for their order using a variety of contactless payment methods, such as Apple Pay, Google Pay, or credit card.</li>
  <li>Once the customer has paid, they can pick up their order from the kitchen or have it delivered to their table.</li>
</ul>

#### Features for Businesses:
<ul>
  <li>Real-time analytics: Businesses can use Dinify.io to track their sales, order volume, and customer feedback in real time. This information can be used to make better decisions about their business.</li>
  <li>Employee management: Businesses can use Dinify.io to manage their employees' schedules and permissions. This helps to ensure that orders are processed quickly and efficiently.</li>
  <li>Integration with other systems: Dinify.io can be integrated with other systems, such as point-of-sale systems and accounting software. This helps to streamline operations and reduce manual work.</li>
</ul>
Overall, Dinify.io is a powerful and versatile contactless dining and takeout solution that can help restaurants and businesses of all sizes improve their operations and customer experience.

## Scope of Improvement according to me:

### Client Facing Application: 
<ul>
  <li>When we click on a food item to add it, the image of the item appears distorted. This is because the width is set to 100%. It can be changed to fit-content so that the image is clear.</li>
</ul>

### Restaurant Dashboard
<ul>
  <li>In Home Page, when we click on takeout order and input customer name and after that wen we select a dish, the customer name is not present. To overcome this, we can store the customer name in session storage and then import it from there.</li>
  <li>When we select the date range the calender to see the orders by week, we are able to select the future dates. This can be resolved by using JQuery maxDate
  /*$(function(){
    var dtToday = new Date();

    var month = dtToday.getMonth() + 1;
    var day = dtToday.getDate();
    var year = dtToday.getFullYear();

    if(month < 10)
        month = '0' + month.toString();
    if(day < 10)
        day = '0' + day.toString();

    var maxDate = year + '-' + month + '-' + day;    
    $('#txtDate').attr('max', maxDate);
});*/
  </li>
  <li>When completing an order, there should be a drop down button to select the mode of payment and also an input box to show the tip amount paid.</li>
  <li>When we place an order from a table, there should be an option to add customer details so that we get an updated list of customers.</li>
  <li>In knowledge base, there is a typo in how to delete/add tables</li>
</ul>

## What makes me excited about the role and how can it help in my career:
<ul>
  <li>I am excited about the opportunity to intern as a software engineer at Dinify.io because I am passionate about the company's mission to make contactless dining and takeout more accessible and convenient. I believe that Dinify.io's solutions have the potential to revolutionize the way people eat, and I am eager to contribute to the company's growth and success.</li>
<li>I am also excited about the opportunity to work on challenging and innovative software engineering projects at Dinify.io.  I am confident that I can learn a lot from the Dinify.io engineering team and contribute to the development of new and innovative products and features.</li>
  <li>Finally, I am excited about the opportunity to gain real-world experience in the software engineering industry at Dinify.io. I have learned a lot in my academic studies, but I am eager to put my skills to the test in a real-world environment. I am confident that an internship at Dinify.io would give me the experience and knowledge I need to succeed in my career as a software engineer.</li>
</ul>







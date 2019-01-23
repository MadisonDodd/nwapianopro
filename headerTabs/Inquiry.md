---
layout: page
title: "Inquiry"
permalink: /inquiry
---

<h1>Inquiry</h1>
<form action="https://formspree.io/nwapianoprollc@gmail.com" method="POST">
    <h5>Enter Inquiry Info below</h5>
    <p>Disclaimer: For the best service and most accurate and timley response please fill out all fields if possible</p>
    Name: <input  size="30" name="name" placeholder="First Name and Last Name"><br/>
    Email: <input size="30" name="email" placeholder="your@name.email" pattern="[a-zA-z0-9\.]+@[a-zA-Z]+\.[a-zA-Z]+" title="Example:mail445@yourmail.com" required><br/>
    Phone Number: <input size="3" maxlength="3" name="areacode" placeholder="000" required> - <input size="7" placeholder="089-0912" name="phonenumber" required><br/>
    Piano Type: <select> 
        <option value="Baby Grand">Baby Grand</option>
        <option value="Big">Big</option>
        <option value="Small">Small</option>
        <option value="Grand">Grand</option>
        <option value="Expensive">Expensive</option>
        <option value="Low cost">Low cost</option>
        <option value="Toy">Toy</option>
    </select>
    <br/>
    Address: <input size="30" name="address"><br/>
    City: <input size="15" name="city"> State <input size="15" name="state"><br/>
    Zipcode: <input size="7" maxlength="7" name="zipcode"><br/>
    Potential Move Date: <input type="date" name="movedate" min="2019-01-01" max="2025-12-31"><br/>
    Special Needs or Comments: <textarea rows="4" cols="50" name="comments"> </textarea>
    <br/>
<input type="submit" value="Submit"/>
<input type="reset" value="Reset Form"/>
</form>
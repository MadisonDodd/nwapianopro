---
layout: page
title: "Inquiry"
permalink: /inquiry
---

<h1>Inquiry</h1>

<form class="bold">
    <h5>Enter Inquiry Info below</h5>
    Name: <input  size="30" name="name" /><br/>
    Email: <input size="30" name="email" /><br/>
    Phone Number: <input size="3" name="areacode"> - <input size="7" name="phonenumber"><br/>
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
    Zipcode: <input size="7" name="zipcode"><br/>
    Potential Move Date: <input type="date" name="movedate" min="2019-01-01" max="2025-12-31"><br/>
    Special Needs or Comments: <textarea rows="4" cols="50"> </textarea>
    <br/>
    <input type="submit" value="Submit"/>
    <input type="reset" value="Reset Form"/>
  </form>
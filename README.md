Download Link: https://assignmentchef.com/product/solved-cist-1305-program-design-and-development-shipping-application
<br>
Computers R Us  would like a report that lists the orders from its online customers. The current open orders are written into an order file, “customerOrders.dat” . Print a report using the contents of this file formatted as shown in the accompanying printer spacing chart. There are computed values, too. Formulas are provided below.  At the end of the report print an accumulated total for all orders.




The shipping code table contains updated shipping information and should be used to load arrays that the program will then use to determine the shipping code, and shipping charge.










<strong>Deliverables:</strong>

<ul>

 <li>The program must be modular. The program should utilize both functions and modules. Include the following:

  <ul>

   <li>A minimum of one library function. o A minimum of one custom function.</li>

   <li>A minimum of one module.</li>

  </ul></li>

 <li>Validation: o Using the shipping code table provided, check for valid shipping code. Print a message on the report instead of the detail line when an invalid code is entered. Include customer name and number in the message.

  <ul>

   <li>Quantity must be at least 1. Print a message instead of the detail line when the quantity value is invalid. Include the customer name and number.</li>

  </ul></li>

</ul>




<strong>Documentation:</strong> Include the following:

<ul>

 <li>Hierarchy chart.</li>

 <li>Internal comments.</li>

 <li></li>

</ul>







<strong>Program assumptions: </strong>

Extended Price of an order = quantity ordered * unit price

Order total = extended price + shipping charge

NOTE: There are no taxes required for this program.

<strong>Shipping Codes and Fees: </strong>

<strong> </strong>

<table width="302">

 <tbody>

  <tr>

   <td width="43">C</td>

   <td width="180">Customer Pick-Up</td>

   <td width="79">00.00</td>

  </tr>

  <tr>

   <td width="43">P</td>

   <td width="180">Parcel Post</td>

   <td width="79">6.25</td>

  </tr>

  <tr>

   <td width="43">R</td>

   <td width="180">Federal Express</td>

   <td width="79">18.55</td>

  </tr>

  <tr>

   <td width="43">U</td>

   <td width="180">UPS Ground</td>

   <td width="79">10.95</td>

  </tr>

  <tr>

   <td width="43">M</td>

   <td width="180">Overnight Mail</td>

   <td width="79">12.50</td>

  </tr>

  <tr>

   <td width="43">A</td>

   <td width="180">AirBorne Express</td>

   <td width="79">14.95</td>

  </tr>

 </tbody>

</table>







<strong>Input File Description:            File:</strong>  <strong>customerOrders.dat </strong>

<strong> </strong>

<table width="409">

 <tbody>

  <tr>

   <td width="194"><u>Field Description </u></td>

   <td width="215"><u>Data Type</u></td>

  </tr>

  <tr>

   <td width="194">Order Number</td>

   <td width="215">Integer</td>

  </tr>

  <tr>

   <td width="194">Customer Name</td>

   <td width="215">String</td>

  </tr>

  <tr>

   <td width="194">Item Number</td>

   <td width="215">Integer</td>

  </tr>

  <tr>

   <td width="194">Quantity Ordered</td>

   <td width="215">Integer</td>

  </tr>

  <tr>

   <td width="194">Unit Price</td>

   <td width="215">Real (2 decimal places)</td>

  </tr>

  <tr>

   <td width="194">Shipping Code</td>

   <td width="215">String</td>

  </tr>

 </tbody>

</table>







<strong><u>Output Report – Printer Spacing Chart:</u> </strong>

<strong> </strong>

Computers R Us

Current Open Orders

<strong> </strong>

Customer Name         Order       Item     Qty.    Unit        Ext.          Ship           Order <strong>                                                              </strong>Number     Num.   Ord.   Price      Price            Cost               Total  XXXXXXXXXXXXXXX    99999        9999    999  999.99   99999.99    99.99   999999.99




<h2>___________________________________________________________________________                                                                                                                          Outstanding Order Balance        $999999999.99</h2>
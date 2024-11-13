# LEARN_JSON

<earlier we used to use xml app which were based on soap rechnology 
SOAP, or Simple Object Access Protocol, is a standard protocol that allows applications to communicate with each other, even if they were built using different languages or on different platforms
JSON (JavaScript Object Notation) and XML (eXtensible Markup Language) are both formats used for storing and exchanging data,
Json is lightweight and uses key value pair and is easier to read and write and is ideal for web and mobile data exchange.it can be used with any programming lang.It supports objects and array 
>



<JSON.parse(json)  >     
 JSON.parse() is used in JavaScript to convert a JSON-formatted string into a JavaScript object.

Receiving JSON Data from an API: When you make an API call and receive JSON as a response, the data comes as a string. To use it as a JavaScript object, you use JSON.parse().




<XML uses tagname  and is more complex and is better for complex structured data >



<Difference between json and xml>
No. JSON

1) JSON stands for JavaScript Object Notation.

2) JSON is simple to read and write.

3) JSON is easy to learn.

4) JSON is data-oriented.

5) JSON doesn't provide display capabilities.

6) JSON supports array.

7) JSON is less secured than XML.

8) JSON files are more human readable than XML.

9)JSON supports oniy text and number data type.


XML

XML stands for eXtensible Markup Language.

XML is less simple than JSON.

XML is less easy than JSON.

XML is document-oriented.

XML provides the capability to display data because it is a markup language

XML doesn't support array.

XML is more secured.

XML files are less human readable.

XML support many data types such as text, number, images, charts, graphs etc. Moreover, XML offeres options for transferring the format or structure of the data with actual



<Similarities between JSON and XIVIL>

✔ Both are simple and open.

✓ Both supports Unicode. So internationalization is supported by JSON and XML both.

Both represents self describing data.

✓ Both are interoperable or language-independent.




<In JSON, values must be one of the following data types:>

a string
a number
an object (JSON object)
an array
a boolean
Null

<JSON values cannot be one of the following data types:>
a function
a date
undefined




<How to retrieve the data stored in JSON object?
You can retrieve or access the values stored in an JSON object in the same way as we access them in JavaScript. The below methods can be used to access the values of JSON object.
**Using dot notation
**Using square brackets>



<What is the JSON.stringify() method used for?
The JSON.stringify() method is used to convert the JavaScript object into a JSON string format.
**JSON.stringify(JSONString, function, space)>
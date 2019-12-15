# JLAObjective1

Objective

The following four questions are designed to get a feel for your understanding of the Java programming language, basic object-oriented design, good programming practices, and ability to learn new material. It is oriented towards server-side development. All of your answers must be compatible with the JDK 1.7. This test is graded on technical merit, attention to detail, and style. 

Your responses to the coding questions must be submitted as .java files which can be compiled. All classes must be placed in the com.componentwise.eval package.

Question 1:
Describe how to implement a simple parser that does well-formedness checking on XML, such as the following: 
<BackgroundCheck>
        <CriminalHistory>
                <HistoryCode>x</HistoryCode>
                < HistoryCode>y</HistoryCode>
                < HistoryCode>z</HistoryCode>
        </CriminalHistory>
</BackgroundCheck>

Please note that using a parser like Xerces is not acceptable.  You can either describe the algorithm, write pseudo code or optionally implement the solution.

# Answer: 
Please note JDK 1.7 was not available for Ubuntu 18.x which I am running on my laptop. I believe the code will work with 1.7, but I cannot verify that on my system. I am running openjdk 11.04

There are many ways to implement a parser to check for well-formedness of an XML document. I chose to use the Java DOM XML Parser. The code I have attached was found at this website:

https://howtodoinjava.com/xml/read-xml-dom-parser-example/
I have attached the following file: ParseXMLStructure.java to the reply email.

But a good walk-throughs were also found at these sites:

https://www.tutorialspoint.com/java_xml/java_dom_parse_document.htm
https://www.youtube.com/watch?v=HfGWVy-eMRc

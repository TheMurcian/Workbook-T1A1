# Workbook-T1A1
Workbook assignment | 

## Q1 Research the development of the internet from 1980 to today. You must describe at least FIVE key events in the development of the internet. You can refer to events, people of significance, or technologies and how they have changed over time. 300 - 500 words

From military experiment to a tool that has become integrated into almost every facet of life, there have been many significant developments with respect to the internet. This short essay will highlight several key events in this development from the 1980’s until today. The first major development of the 1980’s came from Tim Berners-Lee who in 1980 - whilst at the European Organization for Nuclear Research (CERN) - developed ENQUIRE, a notebook program documenting links between people, computers, and also projects - a technique which later became known as hypertext (Press, 2015; Dennis, 2020). This moment proved significant because this initial program gave rise to the idea of the World Wide Web itself. A second major event in the development of the internet arrived in March 1989 when Bernes-Lee began circulating a proposal at CERN entitled “Information Management: A Proposal” which sought to address information loss at the company as well as propose a new way to manage information about accelerators and experiments at CERN (Miller, 2014). The idea was to generate a hypertext-based system over the internet where any part of the text could be linked to a specific document which then, most crucially, could be part of a universally linked system that - as Miller notes - stressed both generality and portability (Miller, 2014). ENQUIRE takes fuller force at CERN, and in the following year the world’s first website and server go live at CERN, along with Bernes-Lee developing the first Web browser, the WorldWideWeb (Pewresearch, 2014). Built over existing IP and TCP protocols, the World Wide Web consisted of: 1) a textual format to represent documents (HTML); 2) a simple protocol allowing exchange between documents (HTTP); 3) a client to display said documents, the first web browser; and 4) a server to give access to a given document (MDN, 2020).

The period between the early 1980’s and especially in the early-to-mid 1990’s saw the transition of the internet from a research and military network, to one accessible by the public, as seen in the decommission of ARPANET in 1990 and by 1991, all four of the world wide web’s building blocks were completed and its servers running outside of CERN (Naughton, 2016; MDN, 2020). This transition to a public project proved another major development in the internet’s history, cemented in 1993 when CERN places it’s technology in the public domain, and in the same year Marc Andreessen proposes IMG HTML tags to allow the display of images - all of which hinting at the potential as well as future trajectory of the internet (Pewresearch, 2014). The final major phase concerning the internet’s development as demarcated by Naughton is from the mid-1990’s until the present, first beginning with the commercialisation of the internet and ending our current state of mobile connectivity, social media, and more recently issues of surveillance and cybercrime (2016). Finally, amongst the most recent developments is the proliferation of social media, chiefly via Mark Zucherberg’s Facebook, which came to dominate the social networking sphere, permanently changing the internet’s landscape. 



## Q2	Define the features of the following technologies that are essential in terms of the development of the internet:
- packets
- IP addresses (IPv4 and IPv6)
- routers and routing
- domains and DNS
## Explain how each technology has contributed to the development of the internet. 50 - 100 words per dot point

### Packets
Data or information that is sent from one device to another is first broken down into what are called packets. Packets of information then carry the data through the internet - along disparate pathways or routes - to a targeted destination in a reliable and efficient manner. An image, for example may be comprised of millions of bits, and too large to be sent by one packet, so it is then broken down into smaller and more manageable packets and, along with a specified IP address, the packets are then sent via the best available route (Cerf, 2019). 

#### IP addresses (IPv4 and IPv6)
An IP or Internet Protocol address is a unique numeric identity of an interface, originally consisting of four numbers (IPv4). IPv6 later replaced IPv4, allowing for 128-bit addresses and better security. Similar to how postal addresses provide a unique identity to a specific house, an IP address likewise provides an unique address - ordered by a hierarchy of information such as country/network or now networks/sub-networks -  to each device (Cerf, 2019). When visiting a website, one’s computer requests another computer for information by sending a message to it’s IP address with an origin address. The IP address thus allows for a correct correspondence between the devices on the internet, allowing global communication communication and exchange. 

#### Routers and Routing
If packets are the accumulated and broken down pieces of information that are sent across networks, routers are a device that connects and forwards the information between computer networks. This process - called routing - is where some type of data, such as an e-email, is sent off with an IP address with the routers functioning as online traffic managers, ensuring the packets navigate smoothly through the network between other routers, as well as bypassing online congestion and selecting the most optimal route (Cerf, 2019).


### Domains and DNS
Domains or domain names are unique site-names or address that direct to a specific website. Simply, the DNS is a directory of names that match with numbers (i.e., IP addresses). Importantly, it will bridge the language gap between humans and computers by resolving names to numbers - that is - domain names to IP addresses by reviewing domain-names within it’s distributed servers and databases to locate a searched domain-name with it’s corresponding IP address (Shaw & Fruhlinger, 2020). This then allows the computer to communicate with the targeted site or web-server and retrieve the webpage. 

# Q 3: Define the features of the following technologies that are essential in terms of the development of the internet (150-300 words per dot point):
 - TCP 
 - HTTP and HTTPS
 - web browsers (requests, rendering and developer tools) 
## Explain how each technology has contributed to the development of client and server communication over the internet 

### TCP:
TCP - Transmission Control Protocol - is a standard which defines how to establish and also maintain a network conversation. TCP, in conjunction with the Internet Protocol (IP) - commonly referred to as the TCP/IP internet  protocol stack or suite -  are the basic rules and parameters defining the internet (Lutkevich, 2020). TCP’s provide secure mechanism by which clients and servers exchange packets of data - that is, end to end communication - making the commonplace client-server architecture possible. In terms of operation, consider that when a web server sends a HTML file to a client, it will employ the hypertext transfer protocol (HTTP) which requests the TCP layer to set up the connection and then send the file (Lutkevich, 2020). TCP stack is crucial because it contains a destination port checksum, but also divides the file into separate data packets, numbers them sequentially, and then will forward each individually to the IP layer for delivery. In term (Anne, 2017). These sequence numbers allow packets to arrive in order, even if they travel via disparate routes to reach the targeted destination. Once an IP address is known, the browser will set up a connection to the server via the TCP three-way handshake - a mechanism designed to allow two communicating entities (ie., the browser and web server) to negotiate the parameters of the network TCP socket connection prior to the transmission of data (MDN, 2020). Finally, the TCP program layer will assemble the packets into a file and then deliver said file to the recipient application, making client and server communication efficient and possible (Lutkevich, 2020). TCPs are important because client-server applications - be they browsers or web servers - employ TCPs and IPs to communicate. Moreover, the fact that the internet in use today - and without which, life would function very differently - is based on the TCP suite of protocols illustrates how significantly this technology has contributed to the development of client and server communication over the internet. 

### HTTP:
Hypertext Transfer Protocol (HTTP) and Hypertext Transfer Protocol Secure (HTTPS) are web protocols - i.e., rules for sending and receiving messages -, and the underlying protocols of the early and modern internet. These protocols allow for the exchange of various types of media and documents over the internet. Importantly, the HTTP was originally one of the central ingredients of what would become the World Wide Web in that it was a means of exchanging early HyperText Markup Language (HTML) documents (MDN Web Docs, 2020). HTTPS is an extension of the HTTP which adds a layer of security via data encryption. Request and response messages with HTTPS are transmitted between the browser and server in an encrypted form, using Secure Sockets Layer, or more recently, Transport Layer Security (Ousterhout, 2010). Berner-Lee’s original hypertext system has seen many changes and developments since the late 1980s and early 1990’s. From a once early protocol used to exchange HTML files and being confined to semi-trusted laboratory environment to its current utilisation in every single continent and carrying advanced media types such as images, 3D, as well as high resolution video, HTTP and it’s subsequent iterations like HTTP/2 has profoundly enhanced and shaped the development of client and server communications all within a quarter of a century (MDN Web Docs, 2020).

### Web browsers (requests, rendering, and developer tools):
If the aforementioned technologies do all the hard work behind the scenes in terms of generating and enabling client-server communication, web browsers communicate with and retrieve from a server in order to display the data visually for clients on the other end. Requests are the first step to navigating to a given webpage. The HTML of a site is located on a given server with a specific IP address, however, if one has never visited the targeted site prior, a DNS lookup must occur and is requested by your browser to retrieve the information, which may also include CSS files, images, and JavaScript. These requests returns a HTML page in binary stream format which is then converted by the browser into a readable text file.

Rendering, with respect to web browsers, is the process of parsing simple HTML - often in conjunction with both JavaScript and CSS objects for example - and displaying the targeted page on the screen. Two important concepts must be highlighted which illustrate the process and development of client-server communications: 1) document object model (DOM); and 2) CSS object model (CSSOM). In the process of returning information and displaying content, HTML elements are then turned into a DOM tree by the rendering engine, whereby said elements are converted into a JavaScript object called a Node (Hiwarale, 2019). In this respect, a DOM is a high-level API provided by the web browser to efficiently render a webpage which allows developments to both access and manipulate the elements, allowing for the production of both a dynamic and rich user experience (Hiwarale, 2019). CSSOM, on the other hand, involves the utilisation of CSS selectors to target DOM elements and initiate properties such as font-size, border, spacing, and colour. Developer tools are another powerful component of web browsers.  Occupying a range of functions, they in essence offer a powerful suite of technologies to developers, ranging from inspecting HTML, CSS, and JavaScript debugging, to informing developers which assets the page has requested and even loading time (MDN, 2020). All of this is easily accessible via the web browser, be it Chrome, Safari, Firefox, and so on. Web browsers' contribution to the development of client-server communication cannot be understated. Browsers allow a visual navigation of websites and applications, connecting users across the world to their targeted server, ensuring an accessible and reliable user experience made possible by requests,  rendering, and developer tools.

## Q 4: Identify THREE data structures used in the Ruby programming language and explain the reasons for using each. 
Data structures are ways of accessing, organising and classifying a collection of data. There are several different data structures used in Ruby, some of which include: 1) Arrays; 2) Hashes; and 3) Binary trees. Importantly, each of the above - as well as every other data structure - excels at different tasks in their own way (Castello, 2019). An array is a list holding zero or more items, stored in an orderly manner, each one after the other without any gaps between them (Castello, 2019). Arrays can be used as a base for containing more advanced data structures; collecting items; as well as to gather results from a running loop (Castello, 2019).  In contrast to arrays which are like lists, hashes operate like dictionaries. Hashes assign values to keys so that said values can be searched by their key. As such, hashes used if one was storing data that resembled a dictionary (ie., words & definition), or even a phone book which contained people’s names and numbers. Other uses, according to Castello, include: counting a string’s characters; finding duplicates within an array; and as mentioned, mapping words to definitions or names to numbers (2019). A binary tree data structure comprising of nodes, with each node containing a ‘left’ pointer’, a ‘right’ pointer, as well as a data element. Whilst there is no built-in binary tree implementation in Ruby, as Castello informs, they still have several uses which include compressing data and also routing tables (Castello, 2019).

## Q 5: Describe the features of interpreters and compilers and how different they are  50-100 words on each way code is executed 

Interpreters and compilers are computer programs and tools that convert the source code of a programming language into a machine-readable form in order for the instructions of a written program to be then understood by a computer or processor (Ionos, 2020). While similar in terms of structure, the central difference between interpreters and compilers, however, is that the former directly executes the instructions in the source programming language, whereas a compiler will translate said instructions into efficient machine code (Tchiro, 2017). As such, a compiler thus takes code produced in a high-level programming language (such as Java) into low-level code that is directly executable by the local computer or by some program (eg., a virtual machine (Tchiro, 2017). Compilers convert the source code in it’s entirety, prior to runtime, into machine code. An interpreter, by contrast, processes a software project’s source code during it’s runtime and acts as an interface between processor and project (Ionos, 2020). 

## Q 6: Identify TWO commonly used programming languages and explain benefits and drawbacks of each. 

### Python
#### Benefits: 
- Versatility: this is perhaps Python’s greatest strength, that is, it’s high utility value and usage in numerous fields of IT. Python is used extensively in data sciences, artificial intelligence and machine learning, as well as web development, and also server automation (Mischook, 2020). Python can also run and work on various platforms, such as Windows, Mac, Linux, and Rasberry PI. 
- It is user-friendly: Python is, in contrast to other languages such as C++, highly user-friendly and easy to learn. As Mischook notes, programming languages live and die by their usability and utility (2020). In addition to Python’s versatility noted above, Python is extremely easy to approach due to it’s simple english-like syntax, readability, large library of standards and toolkits, as well as it’s integration with other programming languages (eg., C and C++) (Eastwood, 2020). All of which makes Python both an easy entry-point to learn programming but also provides the develops with extensive repository of resources. 
- Efficiency: Python’s syntax assists programmers in writing code and projects in fewer steps or lines of code, compared to other popular languages such as C++ or Java (Mindfire Solutions, 2017). Moreover, Python’s extensive support libraries allow developers to write a wide variety of software applications and produce numerous development tasks, in addition to having over 13’000 Python packages to choose from (Mindfire Solutions, 2018). 

#### Draw backs: 
- Mobile development: despite its versatility outlined above, one drawback of Python is it is not presentably suitable for mobile application development. 
- Primarily non-compiled language: as a non-compiled language, Python requires an interpreter to execute, as opposed to a compiler that would be used in other languages such as C++. Consequently, this method causes the execution speed of the final program to be slower than compiled languages  (Mindfire Solutions, 2018). 
- Syntax: Python’s strict syntax is a double-edged sword. Highly readable and simple, but it’s necessary precision can also pose difficulties. Consider the precision requirements of Python’s indentation, as an illustration. 

### Java
#### Benefits: 
- Mobile App Development: in contrast to Python, Java is one of the two official programming languages for the world’s most popular operating system - Android (Mindfire Solutions, 2018). 
- Multi-threading: Java can allow a program to perform many tasks at the same time. This has many advantages, including permitting multiple operations at once which improves efficiency and saves time (Data-flair, 2018).
- Java is platform independent: this means Java code can run on any machine that doesn’t require any special software to be present (Data-flair, 2018). The only consideration is requiring the JVM to be present on the machine. 
#### Draw backs: 
- Steep learning curve: Java excels in many areas, however, it does take time to get accustomed to. This, of course, is contingent upon many factors, not least a developer’s prior experience with object-oriented programming languages, but if one is to contrast it with other languages such as Ruby or Python, the learning curve for Java is a tad steeper. 
- Performance: a common criticism cited as a drawback for developing in Java is Java’s weaker performance and efficiency levels, in comparison to other languages. For example, Java is quite memory-consuming, and substantially slower than natively compiled languages like C++ or C (Data-flair, 2018).

## Q 7: Identify TWO ethical issues from the areas below and discuss the extent to which an IT professional is ethically responsible in terms of the issue.

### Issue 1: access to a user’s personal information (medical, family, financial, personal attributes such as sexuality, religion, or beliefs)

As an IT professional, depending on the nature of one’s work, there is a high probability that one would encounter sensitive and private information and data of one’s users/clients. Whether it is a data analyst working for a bank, a mobile applications developer, or a systems administrator for a school, handingly and having access to the personal, medical, and or financial attributes or information of others is an incredible responsibility and attached with it is a host of moral and ethical obligations and practices. The data under discussion is not only sensitive and personal, but it is submitted willingly as a trust between the user and service-provider - who are given the right to access it to the exclusion of other parties - in order to facilitate some meaningful transaction. The IT professional is thus to a great extent ethically responsible and obliged to behave appropriately with a user’s private and personal data, and only access such information on a computer system when it overlaps and corresponds with the completion of one’s duties as the ITPA Code of Ethics notes. Consequently, an IT professional must commit to a host of ethical considerations and obligations, including but not limited to: 1) integrity; 2) technical competence with client data; 3) professional responsibility towards user information and privacy, including refraining from accessing or utilising data for purposes unrelated to one’s job description and duties. As illustrated, the IT professional is to a great extent ethically responsible for the issue of access to user’s personal information, and must follow appropriate ethical and legal standards. 

Moreover, there are existing legal parameters and ethical frameworks which do provide some guidance and protection for all parties involved when navigating this sphere. The most comprehensive of which is the Privacy Act 1988 which was amended by the Privacy Amendment (Enhancing Privacy Protection) Act 2012, from which the thirteen Australian Privacy Principles (APPs) descend. These principles govern standards, rights and obligations around the collection, usage and disclosure of personal information, as well as an organisation or agency’s governance and accountability thus providing protection and guidance for users, businesses, and IT professionals (OAIC, 2020). Principle 6, for example, delineates the scope for what purposes the acquired personal information can be shared and disclosed. To an extent, this does rely on companies and organisations maintaining a good degree of transparency. However, breaches of APP’s principles can lead to regulatory action as well as penalties, which is indicative of carrying both ethical and legal force, as well as demonstrating that such legal information does indeed aid the development to pursue an ethical course of action when handling and having access to private and sensitive user-information. 


### Issue 2: GPS tracking data and other types of metadata, MAC addresses, hardware fingerprints

Much of the concerns raised above in Issue 1 can be expressed and shared for other types of sensitive data and information, such as GPS tracking and other types of metadata, as well as hardware fingerprints and MAC addresses with respect to the IT professional. The nature of this data, however, is more technical and unlike the types of data outlined in Issue 1, is not necessarily voluntarily passed on and offered, but may be acquired in the process of using a particular service or application. Such metadata, however, is no less sensitive - especially GPS tracking data - and the IT professional must acquaint him or herself with appropriate ethical codes of conduct as well as the legal architecture built around the handling of such data.

Moving towards a more concrete example, this issue is particularly pronounced in the field of mobile app development. This area - in particular with respect to location tracking services - is where IT professionals and developers will encounter a host ethical and legal considerations for which they are, to a great extent, ethically responsible for the issue. There are a number of privacy challenges for mobile applications, some of the most pressing include: 
- User’s contact list
- Internet data usage
- Photographs
- Information about how the user engages and uses the application,
- And importantly, data about the devices location via GPS tracking as well as the collection of other types of metadata

Of particular relevance is the widespread utilisation of location services which are embedded in much of our daily mobile applications. Understandably, these services assist users in connecting with one another as well as  coordinating logistical considerations and planning. The concern arises when attempting to strike a balance between anonymity and app functionality, especially when location services are not at the periphery of an applications function, but rather central. 

Consent as well as transparency, here, appears vital to the ethical considerations of developers and IT professionals relating to the collection of data, be it via GPS or other metadata. As they pertain to the above example of mobile development, the Information Privacy Act (2009) (QLD) (IP Act) and it’s privacy principles are relevant.  Whilst applicable to Queensland, the IP Act along with it’s principle guides such as those of the Office for Information Commission Qld, provides corresponding references to the appropriate and relevant legislating on a given issue wherein an ethical IT professional can consult and find guidance on the issue of privacy and data collection. 

### Case Study: Access to a user’s personal information - Ebay 2014

There are numerous case studies pertaining to breaches of personal information - be it medical, family, financial, personal attributes or otherwise - from which the ethical IT professional may draw many lessons in order to mitigate against ethical breaches. One case study that deserves consideration is the 2014 Ebay data breach. With respect to the chosen case study, and IT ethics more broadly, two considerations and issues will be raised and discussed: 1) appropriate methods of accessing, which includes handling and securing sensitive data to mitigate against ethical breaches; and 2) the level of access - that is, who can and cannot have access to such data.

The 2014 Ebay security breach, briefly, occurred when hackers accessed Ebay’s corporate network and databases via the log-ins of three corporate employees. This resulted in the compromise of over 145 million user’s personal data, including names, email addresses, encrypted passwords, birth-dates, as well as physical addresses and phone numbers (Perlroth, 2014). Fortunately, users' financial or credit card information was stored separately in encrypted formats but this did not prevent hackers from accessing the aforementioned data of users which, with the exception of encrypted passwords, was stored in plain text (Kelly, 2014; Perlroth, 2014). 

At this juncture we may highlight the first of our two ethical issues as they relate to ethical IT practices, that is storing and handling sensitive data that one has access to. The fact that Ebay was storing people’s personal information in plain text without encryption is shocking enough, but this also underscores the importance of ensuring client privacy and security for ethical IT professionals, no matter the type of personal data one is dealing with. On this, sensitive information such as names and contact details should be hashed and encrypted to ensure the privacy of user data and minimise threats to the individual should a security breach take place. The concern here that ought to be highlighted is the fact that robust security was offered for financial details, preventing fraud, however, the same type of protection is not offered for personal details such as those stored in plain text which can very easily lead to identity theft. Encryption of all types of sensitive information is the first step to mitigating against ethical security breaches and an appropriate way of handling clients' private information that one has access to ought to be at the forefront of an ethical IT professional’s concern. 

A second issue of concern is the extent to which developers and employees require access to sensitive information. To mitigate against security breaches in this regard, there must be some level of clearance within a company to ensure that 1) not all developers have access to all of the data; 2) that only a handful do in a circumstance wherein they need to edit or fix something in production; and 3) that not one single individual has sole access - such as the CEO - whereby potentially impeding 2) or needing to be the singular target for hackers.  

Returning EBay, EBay have had to ask whether the employees who had their logins breached actually required access to the databases which held user information. If they did, then tighter security measures - such as those discussed above - are necessary to consider. Thinking more broadly about mitigation practices and IT ethics, however, day-to-day developers only need access to the development and testing version of a product or application; sensitive data is thus specialised and should only be accessible to selected developers when necessary.

Q 8: Explain control flow, using an example from the Ruby programming language. 
 
Control flow or flow of control refers to the order in which a program’s instructions is carried out and executed which is achieved by various conditional statements such as ‘if’, ‘elsif’, ‘case’, ‘while’, ‘until’, ‘for’, as well as ‘loop’, and so on. Conditional statements as well as loops allow programmers to control the flow of their program in an orderly, consistent and coherent fashion, with each stage following from point a to b as the programmer requires. Consider the following example:

 ```ruby
 Puts  “Enter a number”
   a = gets.chomp.to_i

  If a == 3
     Puts “a is 3”
   Elsif a == 4
     Puts “a is 4”
  Else 
     Puts “a is neither 3, nor 4”
End
```

## Q 9: Explain type coercion. 

Type coercion is the process of changing the value of one type of data into another. In order to complete this, there are various methods utilised to pass a specific type of data into another. For example, consider the following:
.to_s will change a piece of data into a string. The S on the end of the method here indicates the target output of the data type (ie., a string). Consider: 25.to_s    # “25”
Strings can also be converted to numbers via .to_i for integers and .to_f for floats: 
“5”.to_i        # 5
“55.5”.to_f   # 55.5

## Q 10: Explain data types, using examples. 
Data types are a means of classifying data and informing the computer how we want to handle specific data in one’s program, as well as a means of storing data inside of variables (Hogan, 2017). The most important of them which are native to Ruby include: text which are held together in strings; whole and decimal numbers such as integers and floats, respectively, as well as symbols and nil - that is, no value. Consider the following examples:
- name = “Dylan” (string)
- occupation = “Programmer” (string)
- age = 26 (integer)
- ishandsome = true (boolean)
- flaws = nil (nil)

# Q. 11: Here’s the problem: “There is a restaurant serving a variety of food. The customers want to be able to buy food of their choice. All the staff just quit, how can you build an app to replace them?”
 - Identify the classes you would use to solve the problem
 - Write a short explanation of why you would use the classes you have identified

### Menu class:
Handles menu option effectively and removes need to staff/waiters
Provides details of name, description, and price of items 
Perhaps utilise a global variable to bring up a list of all dishes when called
Eg: 
```ruby
 class Dish
   Attr_accessor: item, :description, :price
End

Dish1 = Dish.new()
Dish1.item = “Pizza”
Dish1.description = “Meat Lovers Pizza”
Dis1.price = “$10
```

### Delivery class:
Handles coordinating and user-driver features 
Allows delivery timing options and details

## Q. 12 : Identify and explain the error in the code snippet below that is preventing correct execution of the program


### Answer:
```ruby
celsius = gets
fahrenheit = (celsius.to_f * 9 / 5) + 32
print "The result is: "
print fahrenheit
puts "."
```

### Explanation:
Celsius in line 2 requires the .to_f method to convert it into a float from a string in order for the program to run. This allows us to input and output floating numbers to accommodate appropriate and accurate conversion rates from celsius to fahrenheit.  

### Q 13: The code snippet below looks for the first two elements that are out of order and swaps them; however, it is not producing the correct results. Rewrite the code so that it works correctly.

```ruby
arr = [5, 22, 29, 39, 19, 51, 78, 96, 84]
i = 0
while (i < arr.size - 1 and arr[i] < arr[i + 1])
    i = i + 1 end

    j = arr[i]
    arr[i] = arr[i + 1]
    arr[i + 1] = j

    puts arr
```

The above successfully looks for the first two digits out of order in the array  - in our case, 39 and 19 - and successfully swaps them, returning:
5
22
29
19
39
51
78
96
84

## Q 14: Demonstrate your algorithmic thinking through completing the following two tasks, in order:
- Create a flowchart to outline the steps for listing all prime numbers between 1 and 100 (inclusive). Your flowchart should make use of standard conventions for flowcharts to indicate processes, tasks, actions, or operations
- Write pseudocode for the process outlined in your flowchart


#### Pseudocode for process 
Start
Initialize i = 1
If i is in range (1-100) 
j = 2
if i / j is integer
if yes, then check if i = j
if yes, i is a prime
if not
i is not prime
If i / j is not an integer
Then  j = j + 1
Do check again: loop back to 3.b with a new j value
Endif
If prime 
then display i 
Then continue loop and increment i = i + 1
If not prime
Don’t display anything, but increment i = i+ 1 
endif
Loop back to 3	
Else (not within range)
 end program
Endif	


# Q. 15: write pseudocode OR Ruby code for the following problem:

You have access to two variables: raining (boolean) and temperature (integer). If it’s raining and the temperature is less than 15 degrees, print to the screen “It’s wet and cold”, if it is less than 15 but not raining print “It’s not raining but cold”. If it’s greater than or equal to 15 but not raining print “It’s warm but not raining”, and otherwise tell them “It’s warm and raining”.

```ruby
raining = false
temperature = 8

if raining && temperature < 15
    puts "It's wet and cold"
elsif temperature < 15 && !raining 
    puts "It's not raining but cold"
elsif temperature >= 15 && !raining
    puts "It's warm but not raining"
else
    puts "It's warm and raining"
end
```

Or
```ruby
raining = true
temperature = 19

if temperature < 15
    if raining  
        puts "It's wet and cold"
    else
        puts "It's not raining but cold"
        end
else
    if raining  
        puts "It's warm and raining"
    else
        puts "It's warm but not raining"
        end
end
```

Note: both programs do run, however, I condensed the two conditional statements into one using && allowing for more efficiency and less lines of code, whereas the second set of code might be considered a superior way of expressing the code with respect to structure and clarity. I included both as I was not certain which would constitute better practice. 


## Q. 16: An allergy test produces a single numeric score which contains the information about all the allergies the person has (that they were tested for). The list of items (and their value) that were tested are:
 - eggs (1)
 - peanuts (2) 
 - shellfish (4) 
 - strawberries (8) 
 - tomatoes (16)
 - chocolate (32)
 - pollen (64)
 - cats (128)

So if Tom is allergic to peanuts and chocolate, he gets a score of 34.

## Write a program that, given a person’s score can tell them:
 a) whether or not they’re allergic to a given item
 b) the full list of allergies.


### Code:

```ruby
puts "Input your given allergy score: "
num = gets.chomp().to_i

puts num > 255 || num < 1 ? "Invalid score & results. Please input valid score: 1-255" : "Allergens | Results: "

if num >= 128 
   puts "Cats: Positive"
   num = num - 128
else 
   puts "Cats: Negative"
end

if num >= 64
   puts "Pollen: Positive"
   num = num - 64
else 
   puts "Pollen: Negative"
end

if 
   num >= 32
   puts "Chocolate: Positive"
   num = num - 32
else
   puts "Chocolate: Negative"
end

if num >= 16
   puts "Tomatoes: Positive"
   num = num - 16
else
   puts "Tomatoes: Negative"
end

if num >= 8 
   puts "Strawberries: Positive"
   num = num - 8
else
   puts "Strawberries: Negative"
end

if num >= 4 
   puts "Shellfish: Positive"
   num = num - 4
else 
   puts "Shellfish: Negative"
end

if num >= 2
   puts "Peanuts: Positive"
   num = num - 2
else
   puts "Peanuts: Negative"
end

if num >= 1
   puts "Eggs: Positive"
   num = num - 1
else
   puts "Eggs: Negative"
end
```

## References:

Anne, C. (2017). ‘The Internet: Crash Course Computer Science #29’, CrashCourse. Retrieved from: https://www.youtube.com/watch?v=AEaKrq3SpW8&t=194s
Castello, J (2019). ‘An Overview of Data Structures for Ruby Developers ’, Ruby Guides. Retrieved from: https://www.rubyguides.com/2019/04/ruby-data-structures/

Cerf, V. (2019). ‘Packet, routers, and reliability | Internet 101 | Computer Science | Khan Academy’. Retrieved from: https://www.youtube.com/watch?v=aD_yi5VjF78

Cerf, V. (2019). ‘IP addresses and DNS | Internet 101  Computer Science | Khan Academy’. Retrieved from: https://www.youtube.com/watch?v=MwxMsaFFycg

Data Flair (2018). ‘Pros and Cons of Java | Advantages and Disadvantages’, Data Flair Training. Retrieved from: https://data-flair.training/blogs/pros-and-cons-of-java/
Dennis, M. A. (2020). ‘Tim Berners-Lee’, Encyclopedia Britannica, June 4, 2020. Retrieved from:
https://www.britannica.com/biography/Tim-Berners-Lee
 
Eastwood, B. (2020). ‘The 10 Most Popular Programming Languages to Learn in 2020’, Northeastern University Blog. Retrieved from: 
https://www.northeastern.edu/graduate/blog/most-popular-programming-languages/

Hiwarale, U. (2019). ‘How the browser renders a web page? - DOM CSSOM, and Rendering’, Medium. Retrieved from: https://medium.com/jspoint/how-the-browser-renders-a-web-page-dom-cssom-and-rendering-df10531c9969

Kelly, G. (2014). ‘Ebay Suffers Massive Security Breach’, Forbes. Retrieved from:
https://www.forbes.com/sites/gordonkelly/2014/05/21/ebay-suffers-massive-security-breach-all-users-must-their-change-passwords/

Lutkevich, B. (2020). ‘TCP (Transmission Control Protocol)’, Search Networking. Retrieved from: https://searchnetworking.techtarget.com/definition/TCP#:~:text=TCP%20(Transmission%20Control%20Protocol)%20is,of%20data%20to%20each%20other.

MDN Web Docs (2020). ‘Evolution of HTTP’. Retrieved from: 
https://developer.mozilla.org/en-US/docs/Web/HTTP/Basics_of_HTTP/Evolution_of_HTTP

MDN (2020). ‘What are browser developer tools?’, Mozilla Developer Docs. Retrieved from: https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_are_browser_developer_tool

Miller, J. M. (2014). ‘25 Years Later: How a ‘Mesh’ Turned Into the World Wide Web’, PC Mag, March 12. Retrieved from: 
https://www.pcmag.com/news/25-years-later-how-a-mesh-turned-into-the-world-wide-web

Mischook, S. (2020). ‘Why Learn Python in 2021?’, StudioWeb. Retrieved from: 
https://blog.studioweb.com/2020/11/29/why-learn-python-in-2021/

Naughton, J (2016). ‘The evolution of the Internet: from military experiment to General Purpose Technology’, Journal of Cyber Policy, 1:1, pp. 5-28 
https://doi.org/10.1080/23738871.2016.1157619

Office for the Australian Information Centre (2020). ‘Australian Privacy Principles’, retrieved from: https://www.oaic.gov.au/privacy/australian-privacy-principles/australian-privacy-principles-quick-reference/

Office for the Australian Information Centre (2014). ‘Mobile Privacy: A Better Practice Guide for Mobile App Developers’, retrieved from: https://www.oaic.gov.au/privacy/guidance-and-advice/mobile-privacy-a-better-practice-guide-for-mobile-app-developers/

Office for the Information Commission Queensland (2014). ‘Privacy and Mobile Apps’. Retrieved from: https://www.oic.qld.gov.au/guidelines/for-government/guidelines-privacy-principles/applying-the-privacy-principles/privacy-and-mobile-apps

Perlroth, N. (2014). ‘Ebay Urges New Passwords After Breach’, New York Times. Retrieved from: https://www.nytimes.com/2014/05/22/technology/ebay-reports-attack-on-its-computer-network.html

Pew Research (2014). ‘The World Wide Web Timeline’, March 11. Retrieved from: https://www.pewresearch.org/internet/2014/03/11/world-wide-web-timeline/

Press, G. (2015) ‘A Very Short History of the Internet and the Web’, Forbes. Retrieved from:
https://www.forbes.com/sites/gilpress/2015/01/02/a-very-short-history-of-the-internet-and-the-web-2/

Shaw, K. & Fruhlinger, J. (2020). ‘What is DNS and how does it work?’, Network World. Retrieved from: 
https://www.networkworld.com/article/3268449/what-is-dns-and-how-does-it-work.html



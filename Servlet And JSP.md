Dynamic Web Pages
-
The major distinction between a dynamic web page and a static page is that the content of one changes according to the user inputs and the other remains fixed.
Examples of static web page- Contact Info Page
Example of dynamic web page- Social Media platforms

The dynamic web pages include server side processing to generate HTML content based on the user input. One of the major backbone of handling these server side requests and
providing the appropriate response is Java Servlets. Java Servlets are classes that handle these requests and responses on the server side.

Servlets
-
**Understanding the Servlet API:**
- Servlet (Interface)

  -This is the root interface in the Servlet API and contains five abstract methods namely
  *init(ServletConfig config)* , *service(ServletRequest request, ServletResponse response)*, *destroy(), getServletConfig(), getServletInfo().*

- GenericServlet Class(Abstract Class)
  -This abstract class implements the Servlet Interface and is intended to be subclasses by servlet developers. 

- HttpServlet Class(Abstract Class)
  -Another abstract class that implements the Servlet interface and has some additional methods such as *doGet(req,res), doPost(req,res), doPut(req,res), doDelete(req,res)*

Thus to create a servlet there are quite a few ways of doing it.

 - implementing the Servlet interface which will require you to provide implementation of the abstract methods
 - extending the GenericServlet class
 - extending HttpServlet class

An important note: While implementing the Servlet interface directly we also implement a couple more interfaces which are *Serializable* and *ServletConfig.* 











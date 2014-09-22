java.io.FileNotFoundException
=============================

Too many open files

  ERROR [[localhost]] Exception Processing ErrorPage[exceptionType=java.lang.Exception, location=/pages/content/home/Error.jsp]
    org.apache.jasper.JasperException: Unable to compile class for JSP
    at org.apache.jasper.JspCompilationContext.compile(JspCompilationContext.java:574)
    at org.apache.jasper.servlet.JspServletWrapper.service(JspServletWrapper.java:316)
    at org.apache.jasper.servlet.JspServlet.serviceJspFile(JspServlet.java:336)
    at org.apache.jasper.servlet.JspServlet.service(JspServlet.java:265)
    at javax.servlet.http.HttpServlet.service(HttpServlet.java:803)
    at org.apache.catalina.core.ApplicationFilterChain.internalDoFilter(ApplicationFilterChain.java:290)
    at org.apache.catalina.core.ApplicationFilterChain.doFilter(ApplicationFilterChain.java:206)
    at org.apache.catalina.core.ApplicationDispatcher.invoke(ApplicationDispatcher.java:654)
    at org.apache.catalina.core.ApplicationDispatcher.processRequest(ApplicationDispatcher.java:447)
    at org.apache.catalina.core.ApplicationDispatcher.doForward(ApplicationDispatcher.java:379)
    at org.apache.catalina.core.ApplicationDispatcher.forward(ApplicationDispatcher.java:292)
    at org.apache.catalina.core.StandardHostValve.custom(StandardHostValve.java:423)
    at org.apache.catalina.core.StandardHostValve.throwable(StandardHostValve.java:270)
    at org.apache.catalina.core.StandardHostValve.invoke(StandardHostValve.java:141)
    at org.apache.catalina.valves.ErrorReportValve.invoke(ErrorReportValve.java:102)
    at org.jboss.web.tomcat.service.jca.CachedConnectionValve.invoke(CachedConnectionValve.java:157)
    at org.apache.catalina.core.StandardEngineValve.invoke(StandardEngineValve.java:109)
    at org.apache.catalina.connector.CoyoteAdapter.service(CoyoteAdapter.java:262)
    at org.apache.coyote.http11.Http11Processor.process(Http11Processor.java:844)
    at org.apache.coyote.http11.Http11Protocol$Http11ConnectionHandler.process(Http11Protocol.java:583)
    at org.apache.tomcat.util.net.JIoEndpoint$Worker.run(JIoEndpoint.java:446)
    at java.lang.Thread.run(Thread.java:619)
    Caused by: java.io.FileNotFoundException: /usr/local/jboss-4.2.2.GA/server/default/work/jboss.web/localhost/catissuecore/org/apache/jsp/pages/content/home/Error_jsp.java (Too many open files)
    at java.io.FileOutputStream.open(Native Method)
    at java.io.FileOutputStream.<init>(FileOutputStream.java:179)
    at java.io.FileOutputStream.<init>(FileOutputStream.java:70)
    at org.apache.jasper.compiler.Compiler.generateJava(Compiler.java:152)
    at org.apache.jasper.compiler.Compiler.compile(Compiler.java:306)
    at org.apache.jasper.compiler.Compiler.compile(Compiler.java:286)
    at org.apache.jasper.compiler.Compiler.compile(Compiler.java:273)
    at org.apache.jasper.JspCompilationContext.compile(JspCompilationContext.java:566)
    ... 21 more

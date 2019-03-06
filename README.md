# CSD4464-4-Week09
our jsf file 


<?xml version='1.0' encoding='UTF-8' ?>
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml"
      xmlns:h="http://java.sun.com/jsf/html"
      xmlns:f="http://java.sun.com/jsf/core"
      xmlns:ui="http://java.sun.com/jsf/facelets">
    <h:head>
        <title>Facelet Title</title>
    </h:head>
    <h:body>
  <h:form>
      <h:panelGrid columns="3">
      <h:outputLabel value="username" for="usrename"/>
      <h:inputText id="username" required="true" requiredMessage="#{msg['username.validation']}"/>
      <h:message for="username"/>
      
      <f:facet name="footer">
          <h:commandButton value="submit" action="/pages/home/">
              
          </h:commandButton>
      </f:facet>
      </h:panelGrid>
   </h:form>   
   
    </h:body>
</html>




FACE
<?xml version='1.0' encoding='UTF-8'?>
<faces-config version="2.2"
              xmlns="http://xmlns.jcp.org/xml/ns/javaee"
              xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
              xsi:schemaLocation="http://xmlns.jcp.org/xml/ns/javaee http://xmlns.jcp.org/xml/ns/javaee/web-facesconfig_2_2.xsd">
    <application>
        <resource-bundle>
            <base-name>com.FirstApp.props</base-name>
            <var>msg </var>
        </resource-bundle>
    </application>
</faces-config>


HOME
<?xml version='1.0' encoding='UTF-8' ?>
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml"
      xmlns:h="http://xmlns.jcp.org/jsf/html">
    <h:head>
        <title>Home page</title>
    </h:head>
    <h:body>
        <h:outputFormat
    </h:body>
</html>


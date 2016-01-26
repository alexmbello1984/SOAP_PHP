1. La estructura de un mensaje SOAP

   El wsdl es un archivo XML normal cuyo raiz será la envoltura del mensaje SOAP
   

    <wsdl:definitions xmlns:soap="http://schemas.xmlsoap.org/wsdl/soap/"
        xmlns:tns="http://www.example.org/hodelineWebWS/" 
        xmlns:wsdl="http://schemas.xmlsoap.org/wsdl/"	
        xmlns:xsd="http://www.w3.org/2001/XMLSchema" name="hodelineWebWS"
        targetNamespace="http://www.example.org/hodelineWebWS/">
	
        <wsdl:types>...</wsdl:types>

        <wsdl:message>...</wsdl:message>
        <wsdl:message>...</wsdl:message>
        
        <wsdl:portType>...</wsdl:portType>

        <wsdl:binding>...</wsdl:binding>

        <wsdl:service name="hodelineWebWS">...</wsdl:service>

    </wsdl:definitions>

    Los elementos mencionados los iremos analizando del final hacia el inicio.

1.1 
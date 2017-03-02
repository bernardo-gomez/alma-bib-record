# alma-bib-record
 </br>
 <p width="600px">
 web service that receives an alma mms_id and it produces the corresponding MARC record in one of three formats.
 formats:
     - marcxml ,
     - marcedit ( see http://marcedit.reeset.net/features ),
     - text . format created by bernardo gomez. record delimiter is &quot;*****&quot;. subfield delimiter
              is &quot;p\\&quot;
              example: 
                  ******
                  100|10|\\paAuthor
                  245|01|\\paTitle
 web service script works as CGI, and it expects a configuration file as a command line argument.
 configuration file content:
 sys_email=&quot;bgomez@emory.edu&quot;
apikey=&lt;your alma apikey here&gt;
api_host=https://api-na.hosted.exlibrisgroup.com
 </p>
   

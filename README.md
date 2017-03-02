# alma-bib-record
 <br>
 <p width="600px">
 web service that receives an alma mms_id and it produces the corresponding MARC record in one of three formats.
 formats:<br>
     - marcxml ,<br>
     - marcedit ( see http://marcedit.reeset.net/features ),<br>
     - text . format created by bernardo gomez. record delimiter is &quot;*****&quot;. subfield delimiter <br>
              is &quot;\\\p&quot;
              example: 
                  ******
                  100|10|\\\paAuthor
                  245|01|\\\paTitle
 <br>
 </p>
 <p width="600px">
 web service script works as CGI, and it expects a configuration file as a command line argument.
 configuration file content: <br>
 sys_email=&quot;admin@someplace.edu&quot; <br>
apikey=&lt;your alma apikey here&gt; <br>
api_host=https://api-na.hosted.exlibrisgroup.com <br>
 </p>
   

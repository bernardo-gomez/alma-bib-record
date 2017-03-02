# alma-bib-record
web service that receives an alma mms_id and it produces the corresponding MARC record in one of three formats.
 formats:
     - marcxml ,
     - marcedit ( see http://marcedit.reeset.net/features ),
     - text . format created by bernardo gomez. record delimiter is "*****". subfield delimiter
              is "p\\"
              example: 
                  ******
                  100|10|\\paAuthor
                  245|01|\\paTitle
 web service script works as CGI, and it expects a configuration file as a command line argument.
 configuration file content:
 sys_email="bgomez@emory.edu"
apikey=<your alma apikey here>
api_host=https://api-na.hosted.exlibrisgroup.com

   

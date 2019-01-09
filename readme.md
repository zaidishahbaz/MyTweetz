 _________________________________________________________________________________________________________________________________________                                           
                                            TO USE THIS TWITTER APP
                                            
                                            
-Download the source code

-Go to the .env file 
-Update the following with your own twitter API i.e consumer key & twitter access token 

            TWITTER_CONSUMER_KEY=
            TWITTER_CONSUMER_SECRET=
            TWITTER_ACCESS_TOKEN=
            TWITTER_ACCESS_TOKEN_SECRET=_
           
          
 _________________________________________________________________________________________________________________________________________ 
Since Laravel, by default, ignores the .env - this is very much intended, as your different environments should technically have, well, different env files. It also helps you from not submitting credentials (such as for your database) into version control.
So you can go ahead and add a .env file in your local machine .

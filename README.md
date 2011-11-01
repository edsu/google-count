`google-count` is a simplistic SEO tool to monitor the coverage for a 
particular domain in Google. google-count prints out the current time and 
the number of google hits for a particular domain. 

Put something like this in your crontab to track a website every hour:

    0 * * * * /home/ed/Projects/google-count/google-count id.loc.gov >> /home/ed/Projects/google-count/logs/id.loc.gov

You might be surprised at how much things fluctuate, and how much your traffic
changes based on it :-)

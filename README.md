# Phishing-Test-Identifier
Catches those pesky fake phishing emails your company sends out.

This addon should ask you to set a trigger for function execution. 
I recommend hourly, since non-premimum gmail accounts can only search through 1500 threads in 24 hours. 
With a trigger set for hourly, make sure to double check any suspicious emails you have received within the last hour 
as the script may not have been executed since receiving the fake phishing email from your employer.

Just add the script from the Google Workspace Marketplace. From there it will create a label named "Phishing Tests" and begin scanning the first 50 emails in your main inbox hourly for the word "phishing" in the emails meta data.

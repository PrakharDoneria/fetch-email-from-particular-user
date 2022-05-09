# fetch-email-from-particular-user
<H1> Implementation: </h1>
The libraries used in this implementation includes imaplib, email. You have to manually go and make IMAP access enabled by going into your Gmail account <a href="https://mail.google.com/mail/u/0/#settings/fwdandpop" target="blank">settings</a>. After this only you could access your Gmail account without logging in browser.

<Br><br>
<Li>Three functions are defined in the implementation which is used to get email body, search for emails from a particular user and get all emails under a label.
<Li>For showing results I have sent email to my id from my another Gmail account. Now I will be fetching emails from my Gmail account which is received from my another Gmail account.
<Li>The process begins from making Gmail connection with the help of imaplib library and proving our Gmail login credentials to it.
<Li>After logging we are selecting emails under the label: Inbox which is a default labeled section for all users. However, you can create your own labels also.
<Li>Then we are calling get emails function and provide it the parameter from search function result i.e “from user”
<Li>In get emails function we are putting all emails in an array named “msgs”
<Li>Now print to see the msgs array
<Li>Now we can easily iterate over this array. We are iterating it in the order the emails arrived. Then we are searching for the index from where our content begins. This indexing part will be different for different emails/users and the user can manually change the indexes to print only that part which they require.
<Li>We have our results printed out.
<Br><br>
<H3>Output: </h3>
<IMG src="https://media.geeksforgeeks.org/wp-content/uploads/20190524175434/gmail_python_2.png" alt="output image screenshot">

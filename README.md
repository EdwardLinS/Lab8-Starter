# Lab8-Starter

Edward Lin
http://edward.techkyra.com/Lab8-Starter/

How are graceful degradation and service workers related?

In graceful degradation, we want to fail with grace by starting with maximum technology and then adding catches for when things fail. Service workers cache network requests in the case of low or no connectivity. Because of their utility, service workers allow our website to be able to fail gracefully in the case of low or no connectivity. We start with maximum technology, high connectivity to the internet, and allow service workers to catch the issue if it ever arises. We are able to catch the problems and still allow users to be able to use the page without much change.
# Autodiscovering-the-great-leak
Autodiscover, a protocol used by Microsoft Exchange for automatic configuration of clients such as Microsoft Outlook, has a design flaw that causes the protocol to “leak” web requests to Autodiscover domains outside of the user’s domain but in the same TLD (i.e. Autodiscover.com).

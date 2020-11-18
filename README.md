# Ethical Email Manifesto

v0.1.1 - Draft

## 1. Preamble
  ### 1.1 Who is this for?

  If you send an email newsletter, onboarding emails for your app or business, or any other form of recurring email subscription and want to make sure you are acting ethically on behalf of your recipients.

  ### 1.2 Why do we need this?

  Unsolicited spam emails are easy to deal with automatically, we can block unknown senders, scan messages for certain keywords, or filter messages that come from specific IP addresses or locations. These are the mails that end up in your SPAM folder without you having to do anything.

  However, many unwanted emails start out with our consent, but our interest in receiving them quickly diminishes over time - so called "graymail". This documnent specifies how we as senders should approach these kind of communications.  
  

## 2. Terms

### 2.1 Don't send unsolicited emails

Above all else, recurring emails should be opt-in, not a surprise. 

In real terms this means;

- Newletter creators; if someone signed up for your monthly newsletter, then don't sometimes send them weekly without asking. 
- App makers; a welcome email is okay, but don't automatically add a new user to your automated drip campaign of 10 onboarding emails. 


### 2.3 Let recipients easily unsubscribe

Being granted permission to send an email to a persons inbox should be treated as a priviledge, and we should respect their right to easily deny us that permission at any time and for any reason.

This means we must provide an unsubscribe link within each email that is accessible to the recipient, this link should unsubscribe in *one click*, and not require any additional steps. 

The link should be clear and purposeful by;
- using clear language. "Click here to unsubscribe" is **good**, "Manage your preferences here" is **not**.
- having a high contrast ratio. Don't hide your links by using light grey text on a white background. This is not cool.

In addition, try to provide a machine-readable `List-Unsubscribe` header [RFC 2369]. This allows automated tools to help your recipients unsubscribe. 

### 3.3. Make intent clear

There should be no doubt why someone is receiving your email,

## 3.

# Resources

1. [RFC 2369 - 3.2 The List-Unsubscribe Header](https://www.ietf.org/rfc/rfc2369.txt)
# Contribution

The undersigned have agreed to abide by the terms of this document;


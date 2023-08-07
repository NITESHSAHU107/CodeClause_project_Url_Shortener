# URL Shortener

## Description
URL Shortener is a Python web application that allows users to shorten long URLs into compact, shareable links. This project was developed as part of the CodeClouse Python Development Internship.

The URL Shortener project aims to create a web application that allows users to convert long URLs into shorter and more manageable versions. The application will provide a user-friendly interface where users can input a long URL and receive a shortened version, which they can easily share on social media, in emails, or other platforms with character limitations. The project will use Python for backend logic, a web framework for handling user requests, and a database to store and retrieve the mappings between long and shortened URLs.


## Features
- Given a long URL, the service should generate a shorter and unique alias for it.
  When the user hits a short link, the service should redirect to the original link.
- Redirect users to the original long URL from the shortened link.
- Links will expire after a standard default time span.
- The system should be highly available. This is really important to consider because if the service goes down, all the URL redirection 
  will start failing.
- URL redirection should happen in real-time with minimal latency.
- Shortened links should not be predictable.


## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your proposed changes.

## Credits
Developed by Nitesh Sahu

## Contact
For any inquiries or questions, feel free to reach out to me at 10799nsahu@gmail.com

# SecretPixels
This website lets you hide secret messages in PNG pictures and read them later. It changes the green part of the picture just a little, so no one can tell there's a message inside. You can upload a picture to find a hidden message or put your own message into a new one.
Name: Ella Augustine
Email: ellaaug@udel.edu
Help Resources Used
I completed this project primarily on my own using only the official Drafter documentation. I didn’t use any external websites, but I did receive occasional help from the course TAs when I had questions about the assignment requirements or how to fix specific errors. Their support helped get the site to work as intended.

Planning Documents
Plan, https://docs.google.com/document/d/1buLTVQVX2_Xrux-pUYI6IDnpQ1x4DQk1pzjQECjo5Os/edit?usp=sharing

Requirements Checklist
7 Routes: I created seven routes — index, display_image, encode, about, view_logs, clear_logs, and message_info.

5 Pages: Each route returns its own Page, giving the site more than five pages total.

State Dataclass with 4 Fields: My State dataclass includes four fields: image, message, logs, and filename.

4 State Fields Modified: All four fields are changed in at least one route. Image and filename are updated when an image is uploaded, the message is set when decoding or encoding, and logs are updated with activity or cleared.

3 Input Fields: I used TextBox for entering a message, and FileUpload for uploading images. (Optionally, more inputs like a CheckBox or SelectBox could be added.)

3 Meaningful If Statements: I used several if-statements to check for input conditions and message existence — for example, in encode, get_message_length, and message_info.

1 Loop Over List or Dictionary: I used loops to go through image pixels and bit groups — for example, in get_color_values, hide_bits, and decode_chars.

Legitimate Purpose: The site lets users hide and extract secret messages in PNG images using steganography, which is a real and useful functionality.

No Global Variables: All information is passed through the State object — no global variables are used.

Only Approved Libraries Used: I only used Drafter, Bakery, and built-in Python libraries (including Pillow for image handling).

Video URL
<(https://drive.google.com/file/d/10cmkKoodR7IkD4K1pQhOvAQkwPUbf5Yt/view?usp=sharing)>

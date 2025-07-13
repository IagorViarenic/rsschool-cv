# Iagor Viarenich

## Contact Information
- **Email**: iagorviarenich@gmail.com

## About Me
I am a passionate and self-motivated aspiring developer with a strong desire to build a career in software development. My goal is to create efficient, user-friendly applications while continuously expanding my technical expertise. Although I have no formal work experience, I am driven by a curiosity for technology and a commitment to mastering new skills. I thrive in challenging environments, leveraging my problem-solving abilities and dedication to learning to deliver high-quality solutions. My focus is on writing clean, maintainable code and staying updated with industry trends to contribute effectively to innovative projects.

## Skills
- **Programming Languages**: PHP, HTML, CSS, JavaScript
- **Tools & Technologies**: Git
- **Methodologies**: Basic understanding of Agile development practices
- **Development Tools**: VS Code, browser developer tools

## Code Sample
Below is a simple PHP function to validate an email address:

```php
function isValidEmail($email) {
    return filter_var($email, FILTER_VALIDATE_EMAIL) !== false;
}

// Example usage
$email = "example@domain.com";
if (isValidEmail($email)) {
    echo "Valid email address";
} else {
    echo "Invalid email address";
}

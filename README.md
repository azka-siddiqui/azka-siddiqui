class Azka:
    def __init__(self):
        self.name = "Azka Siddiqui"
        self.school = "St. Joseph Secondary School"
        self.vscode_theme = "After Dark" #I love this color theme and thought it was important to mention :)
        self.code = {
            "frontend": ["JavaScript", "React.js", "Next.js", "Bootstrap", "Chakra UI", "Tailwind CSS", "HTML", "CSS"],
            "backend": ["Python", "Node.js", "Java", "Azure Functions", "PostgreSQL", "AWS Lambda", "C"],
            "mobile": ["React Native"],
            "tools": ["Git", "GitHub", "GitHub Actions", "Bash", "Linux"]
        }
        self.description = "I'm a junior at St. Joseph Secondary School. 🙂 I love making fun and random applications, or building websites for nonprofits and local businesses! Feel free to reach out and say hello :)"

    def get_contacts(self):
        return {
            "email": "azkasiddiqui240@gmail.com",
            "linkedin": "linkedin.com/in/azkasiddiqui",
            "github": "github.com/azka-siddiqui",
        }

if __name__ == "__main__":
    me = Azka()

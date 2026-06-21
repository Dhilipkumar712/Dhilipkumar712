class DhilipKumar:
    def __init__(self):
        self.name = "Dhilip Kumar"
        self.location = "Chennai, Tamil Nadu, India"
        self.degree = "B.E/B.Tech - Computer Science"
        self.institute = "NxtWave Institute of Advanced Technologies"

        self.stack = [
            "Python", "JavaScript", "HTML5", "CSS3",
            "React.js", "Vite", "Tailwind CSS"
        ]

        self.currently_learning = [
            "Generative AI", "LLM Agent Workflows",
            "AI Workflow Automation", "System Design"
        ]

        self.fun_fact = "I once built a chess app just to understand state management better ♟️"

    def motto(self):
        return "Learn it. Build it. Ship it."

me = DhilipKumar()
print(me.motto())

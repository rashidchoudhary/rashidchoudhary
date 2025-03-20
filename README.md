import { Github, Mail, Code, Database, Server, Cloud, Palette, Terminal, GitBranch } from "lucide-react"

export default function GitHubProfile() {
  return (
    <div className="max-w-4xl mx-auto p-6 bg-white dark:bg-gray-900 text-gray-800 dark:text-gray-200">
      <header className="text-center mb-8">
        <h1 className="text-3xl font-bold mb-2">Hey there 👋, I'm Rashid Ali</h1>
        <h3 className="text-xl text-gray-600 dark:text-gray-400">Student | Full Stack Web Developer | Team Player</h3>
        <div className="border-b border-gray-300 dark:border-gray-700 w-24 mx-auto my-6"></div>
      </header>

      <section className="mb-8">
        <div className="flex flex-wrap gap-4 mb-4">
          <div className="bg-blue-50 dark:bg-blue-900/20 p-3 rounded-lg">
            <span className="font-medium">🌱 Currently Learning:</span> NestJS | AWS
          </div>
          <div className="bg-green-50 dark:bg-green-900/20 p-3 rounded-lg">
            <span className="font-medium">💬 Ask me about:</span> JavaScript, TypeScript, React, Node.js, Databases
          </div>
          <div className="bg-purple-50 dark:bg-purple-900/20 p-3 rounded-lg flex items-center gap-2">
            <span className="font-medium">📫 Reach me at:</span>
            <a
              href="mailto:rashidchoudhary1052@gmail.com"
              className="text-blue-600 dark:text-blue-400 hover:underline flex items-center gap-1"
            >
              <Mail className="w-4 h-4" />
              rashidchoudhary1052@gmail.com
            </a>
          </div>
        </div>
      </section>

      <section className="mb-8">
        <h2 className="text-2xl font-bold mb-6 flex items-center gap-2">
          <Code className="w-6 h-6" />
          My Tech Stack
        </h2>

        <div className="space-y-8">
          {/* Backend */}
          <div>
            <h3 className="text-xl font-semibold mb-4 flex items-center gap-2">
              <Server className="w-5 h-5" />
              Backend
            </h3>
            <div className="flex flex-wrap gap-2">
              {[
                "Node.js",
                "Express.js",
                "NestJS",
                "REST API",
                "WebSockets",
                "Microservices",
                "Redis",
                "Prisma",
                "TypeORM",
                "Mongoose",
              ].map((tech) => (
                <span
                  key={tech}
                  className="bg-green-100 dark:bg-green-900/30 text-green-800 dark:text-green-300 px-3 py-1 rounded-md text-sm font-medium"
                >
                  {tech}
                </span>
              ))}
            </div>
          </div>

          {/* Database */}
          <div>
            <h3 className="text-xl font-semibold mb-4 flex items-center gap-2">
              <Database className="w-5 h-5" />
              Database
            </h3>
            <div className="flex flex-wrap gap-2">
              {["MongoDB", "PostgreSQL", "MySQL", "SQL Server"].map((tech) => (
                <span
                  key={tech}
                  className="bg-blue-100 dark:bg-blue-900/30 text-blue-800 dark:text-blue-300 px-3 py-1 rounded-md text-sm font-medium"
                >
                  {tech}
                </span>
              ))}
            </div>
          </div>

          {/* Cloud Platforms */}
          <div>
            <h3 className="text-xl font-semibold mb-4 flex items-center gap-2">
              <Cloud className="w-5 h-5" />
              Cloud Platforms
            </h3>
            <div className="flex flex-wrap gap-2">
              <span className="bg-yellow-100 dark:bg-yellow-900/30 text-yellow-800 dark:text-yellow-300 px-3 py-1 rounded-md text-sm font-medium">
                AWS (Lambda | S3 | EC2 | Cognito)
              </span>
            </div>
          </div>

          {/* DevOps & CI/CD */}
          <div>
            <h3 className="text-xl font-semibold mb-4 flex items-center gap-2">
              <GitBranch className="w-5 h-5" />
              DevOps & CI/CD
            </h3>
            <div className="flex flex-wrap gap-2">
              {["GitHub Actions", "Docker"].map((tech) => (
                <span
                  key={tech}
                  className="bg-indigo-100 dark:bg-indigo-900/30 text-indigo-800 dark:text-indigo-300 px-3 py-1 rounded-md text-sm font-medium"
                >
                  {tech}
                </span>
              ))}
            </div>
          </div>

          {/* Payment Gateways */}
          <div>
            <h3 className="text-xl font-semibold mb-4">Payment Gateways</h3>
            <div className="flex flex-wrap gap-2">
              <span className="bg-purple-100 dark:bg-purple-900/30 text-purple-800 dark:text-purple-300 px-3 py-1 rounded-md text-sm font-medium">
                Stripe
              </span>
            </div>
          </div>

          {/* Frontend & UI/UX */}
          <div>
            <h3 className="text-xl font-semibold mb-4 flex items-center gap-2">
              <Palette className="w-5 h-5" />
              Frontend & UI/UX
            </h3>
            <div className="flex flex-wrap gap-2">
              {[
                "React",
                "Next.js",
                "Redux",
                "HTML5",
                "Bootstrap",
                "Material UI",
                "TailwindCSS",
                "Ant Design",
                "DaisyUI",
                "Styled Components",
              ].map((tech) => (
                <span
                  key={tech}
                  className="bg-pink-100 dark:bg-pink-900/30 text-pink-800 dark:text-pink-300 px-3 py-1 rounded-md text-sm font-medium"
                >
                  {tech}
                </span>
              ))}
            </div>
          </div>

          {/* Programming Languages */}
          <div>
            <h3 className="text-xl font-semibold mb-4 flex items-center gap-2">
              <Terminal className="w-5 h-5" />
              Programming Languages
            </h3>
            <div className="flex flex-wrap gap-2">
              {["JavaScript", "TypeScript", "Python", "Java", "Kotlin", "C#", "C++", "PHP"].map((tech) => (
                <span
                  key={tech}
                  className="bg-orange-100 dark:bg-orange-900/30 text-orange-800 dark:text-orange-300 px-3 py-1 rounded-md text-sm font-medium"
                >
                  {tech}
                </span>
              ))}
            </div>
          </div>

          {/* Testing & API Docs */}
          <div>
            <h3 className="text-xl font-semibold mb-4">Testing & API Docs</h3>
            <div className="flex flex-wrap gap-2">
              {["Postman", "Swagger"].map((tech) => (
                <span
                  key={tech}
                  className="bg-red-100 dark:bg-red-900/30 text-red-800 dark:text-red-300 px-3 py-1 rounded-md text-sm font-medium"
                >
                  {tech}
                </span>
              ))}
            </div>
          </div>

          {/* Tools */}
          <div>
            <h3 className="text-xl font-semibold mb-4">Tools</h3>
            <div className="flex flex-wrap gap-2">
              {["VS Code", "Nodemon"].map((tech) => (
                <span
                  key={tech}
                  className="bg-teal-100 dark:bg-teal-900/30 text-teal-800 dark:text-teal-300 px-3 py-1 rounded-md text-sm font-medium"
                >
                  {tech}
                </span>
              ))}
            </div>
          </div>

          {/* Version Control */}
          <div>
            <h3 className="text-xl font-semibold mb-4">Version Control</h3>
            <div className="flex flex-wrap gap-2">
              {["Git", "GitHub"].map((tech) => (
                <span
                  key={tech}
                  className="bg-gray-100 dark:bg-gray-800 text-gray-800 dark:text-gray-300 px-3 py-1 rounded-md text-sm font-medium"
                >
                  {tech}
                </span>
              ))}
            </div>
          </div>
        </div>
      </section>

      <section className="mb-8">
        <h2 className="text-2xl font-bold mb-6">🔥 How I Work</h2>
        <div className="grid grid-cols-1 md:grid-cols-2 gap-4">
          {[
            "🚀 I follow Agile & Scrum methodologies",
            "🤝 I believe in teamwork & collaboration",
            "👨‍💻 I advocate pair programming & code reviews",
            "⚡ I emphasize automation & CI/CD",
            "📝 I value documentation & knowledge sharing",
            "🏗 I maintain clean code & clean architecture principles",
            "📚 Passionate about learning",
          ].map((item, index) => (
            <div key={index} className="bg-gray-50 dark:bg-gray-800/50 p-3 rounded-lg">
              {item}
            </div>
          ))}
        </div>
      </section>

      <footer className="text-center pt-6 border-t border-gray-300 dark:border-gray-700">
        <p className="text-gray-600 dark:text-gray-400">⭐ If you like what I do, give my repositories a star! 🚀</p>
        <div className="mt-4 flex justify-center gap-4">
          <a
            href="https://github.com/yourusername"
            className="text-gray-600 dark:text-gray-400 hover:text-gray-900 dark:hover:text-white"
          >
            <Github className="w-6 h-6" />
            <span className="sr-only">GitHub</span>
          </a>
          <a
            href="mailto:rashidchoudhary1052@gmail.com"
            className="text-gray-600 dark:text-gray-400 hover:text-gray-900 dark:hover:text-white"
          >
            <Mail className="w-6 h-6" />
            <span className="sr-only">Email</span>
          </a>
        </div>
      </footer>
    </div>
  )
}


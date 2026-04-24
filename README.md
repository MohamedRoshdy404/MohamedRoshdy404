export default function Portfolio() {
  return (
    <div className="bg-[#0f172a] text-white min-h-screen">

      {/* HERO */}
      <section className="text-center py-20">
        <img
          src="https://media.giphy.com/media/SWoSkN6DxTszqIKEqv/giphy.gif"
          className="mx-auto w-[500px]"
        />

        <h1 className="text-4xl font-bold mt-6">
          Hi 👋, I'm Mohamed Roshdy
        </h1>

        <p className="text-gray-400 mt-3">
          Full Stack .NET Developer | Backend Focused Engineer
        </p>

        <div className="mt-5 space-x-3">
          <a href="https://github.com" className="bg-blue-600 px-4 py-2 rounded">
            GitHub
          </a>
          <a href="https://linkedin.com" className="bg-blue-500 px-4 py-2 rounded">
            LinkedIn
          </a>
        </div>
      </section>

      {/* ABOUT */}
      <section className="px-10 py-10 text-center">
        <h2 className="text-2xl font-bold">🧠 About Me</h2>
        <p className="text-gray-400 mt-3">
          Full Stack .NET Developer focused on backend, system design,
          clean architecture and scalable applications.
        </p>
      </section>

      {/* SKILLS */}
      <section className="px-10 py-10 text-center">
        <h2 className="text-2xl font-bold">⚙️ Skills</h2>

        <div className="grid grid-cols-2 md:grid-cols-4 gap-4 mt-5">
          {[
            ".NET",
            "C#",
            "SQL Server",
            "ASP.NET Core",
            "JS",
            "OOP",
            "DS",
            "EF Core"
          ].map((skill) => (
            <div key={skill} className="bg-gray-800 p-3 rounded">
              {skill}
            </div>
          ))}
        </div>
      </section>

      {/* PROJECTS */}
      <section className="px-10 py-10 text-center">
        <h2 className="text-2xl font-bold">🚀 Projects</h2>

        <div className="grid md:grid-cols-2 gap-6 mt-5">

          <div className="bg-gray-800 p-5 rounded">
            <h3 className="font-bold">🏦 Bank System</h3>
            <p className="text-gray-400 text-sm mt-2">
              A system built with ADO.NET + 3-Tier Architecture
            </p>
          </div>

          <div className="bg-gray-800 p-5 rounded">
            <h3 className="font-bold">📄 Licenses System</h3>
            <p className="text-gray-400 text-sm mt-2">
              Role-based system with full CRUD operations
            </p>
          </div>

        </div>
      </section>

      {/* CONTACT */}
      <section className="text-center py-10">
        <h2 className="text-2xl font-bold">📬 Contact</h2>
        <p className="text-gray-400 mt-2">
          contact.mohamedroshdy@gmail.com
        </p>
      </section>

    </div>
  );
}

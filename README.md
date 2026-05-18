export default function PortfolioPage() {
  return (
    <div className="min-h-screen bg-black text-white font-sans">
      {/* Hero Section */}
      <section className="relative overflow-hidden">
        <div className="absolute inset-0 bg-gradient-to-br from-blue-500/20 via-purple-500/10 to-cyan-500/20 blur-3xl"></div>

        <div className="relative max-w-7xl mx-auto px-6 py-24 lg:py-32">
          <div className="grid lg:grid-cols-2 gap-14 items-center">
            <div>
              <p className="text-cyan-400 text-lg mb-4 tracking-wide">
                👋 Hello, I'm
              </p>

              <h1 className="text-5xl lg:text-7xl font-extrabold leading-tight">
                ATUL
                <span className="block text-transparent bg-clip-text bg-gradient-to-r from-cyan-400 to-blue-500">
                  YADAV
                </span>
              </h1>

              <p className="mt-8 text-gray-300 text-lg leading-8 max-w-2xl">
                B.Tech CSE (AI & ML) Student passionate about Python,
                Full Stack Development, AI technologies, and building
                modern digital experiences.
              </p>

              <div className="flex flex-wrap gap-4 mt-10">
                <a
                  href="https://github.com/Atulyadav12135"
                  target="_blank"
                  className="px-6 py-3 rounded-2xl bg-cyan-500 hover:bg-cyan-400 transition font-semibold text-black shadow-lg shadow-cyan-500/30"
                >
                  View GitHub
                </a>

                <a
                  href="https://www.linkedin.com/in/atulyadav12135"
                  target="_blank"
                  className="px-6 py-3 rounded-2xl border border-white/20 hover:border-cyan-400 hover:text-cyan-400 transition"
                >
                  LinkedIn
                </a>
              </div>

              <div className="grid grid-cols-3 gap-6 mt-14">
                <div className="bg-white/5 border border-white/10 rounded-2xl p-5 backdrop-blur-sm">
                  <h3 className="text-3xl font-bold text-cyan-400">2+</h3>
                  <p className="text-gray-400 mt-2 text-sm">Projects Built</p>
                </div>

                <div className="bg-white/5 border border-white/10 rounded-2xl p-5 backdrop-blur-sm">
                  <h3 className="text-3xl font-bold text-cyan-400">2026</h3>
                  <p className="text-gray-400 mt-2 text-sm">Graduation Year</p>
                </div>

                <div className="bg-white/5 border border-white/10 rounded-2xl p-5 backdrop-blur-sm">
                  <h3 className="text-3xl font-bold text-cyan-400">AI/ML</h3>
                  <p className="text-gray-400 mt-2 text-sm">Specialization</p>
                </div>
              </div>
            </div>

            <div className="relative flex justify-center">
              <div className="absolute w-80 h-80 bg-cyan-500/20 rounded-full blur-3xl"></div>

              <div className="relative bg-gradient-to-br from-white/10 to-white/5 border border-white/10 backdrop-blur-lg rounded-[2rem] p-10 shadow-2xl w-full max-w-md">
                <div className="w-40 h-40 rounded-full bg-gradient-to-br from-cyan-400 to-blue-600 mx-auto flex items-center justify-center text-6xl font-bold shadow-lg shadow-cyan-500/30">
                  AY
                </div>

                <h2 className="text-3xl font-bold text-center mt-8">
                  ATUL YADAV
                </h2>

                <p className="text-center text-gray-400 mt-3">
                  Python Developer • Full Stack Learner • AI Enthusiast
                </p>

                <div className="mt-8 space-y-4 text-sm text-gray-300">
                  <div className="flex items-center justify-between border-b border-white/10 pb-3">
                    <span>Email</span>
                    <span>atulyadav91611@gmail.com</span>
                  </div>

                  <div className="flex items-center justify-between border-b border-white/10 pb-3">
                    <span>Education</span>
                    <span>B.Tech CSE AI&ML</span>
                  </div>

                  <div className="flex items-center justify-between pb-1">
                    <span>Batch</span>
                    <span>2022 - 2026</span>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      {/* Skills Section */}
      <section className="max-w-7xl mx-auto px-6 py-24">
        <div className="text-center mb-16">
          <h2 className="text-4xl lg:text-5xl font-bold">
            Skills & Technologies
          </h2>
          <p className="text-gray-400 mt-4 text-lg">
            Technologies I am learning and working with.
          </p>
        </div>

        <div className="grid sm:grid-cols-2 lg:grid-cols-4 gap-6">
          {[
            "Python",
            "HTML5",
            "CSS3",
            "JavaScript",
            "React",
            "Git & GitHub",
            "AI & ML",
            "Full Stack Development",
          ].map((skill) => (
            <div
              key={skill}
              className="group bg-white/5 border border-white/10 hover:border-cyan-400 transition rounded-3xl p-8 text-center hover:-translate-y-2 duration-300"
            >
              <div className="text-2xl font-semibold group-hover:text-cyan-400 transition">
                {skill}
              </div>
            </div>
          ))}
        </div>
      </section>

      {/* Projects Section */}
      <section className="bg-white/5 py-24">
        <div className="max-w-7xl mx-auto px-6">
          <div className="text-center mb-16">
            <h2 className="text-4xl lg:text-5xl font-bold">
              Featured Projects
            </h2>
            <p className="text-gray-400 mt-4 text-lg">
              Some projects I have worked on recently.
            </p>
          </div>

          <div className="grid lg:grid-cols-2 gap-8">
            <div className="bg-black/40 border border-white/10 rounded-3xl p-8 hover:border-cyan-400 transition duration-300">
              <div className="h-52 rounded-2xl bg-gradient-to-br from-cyan-500/30 to-blue-500/20 mb-6"></div>

              <h3 className="text-3xl font-bold mb-4">CryptoTracker App</h3>

              <p className="text-gray-400 leading-7">
                A cryptocurrency tracking application that displays real-time
                market trends, prices, and analytics using modern web
                technologies.
              </p>

              <button className="mt-6 px-5 py-3 rounded-xl bg-cyan-500 text-black font-semibold hover:bg-cyan-400 transition">
                View Project
              </button>
            </div>

            <div className="bg-black/40 border border-white/10 rounded-3xl p-8 hover:border-cyan-400 transition duration-300">
              <div className="h-52 rounded-2xl bg-gradient-to-br from-purple-500/30 to-pink-500/20 mb-6"></div>

              <h3 className="text-3xl font-bold mb-4">Flipkart UI Clone</h3>

              <p className="text-gray-400 leading-7">
                A responsive Flipkart-inspired user interface focused on modern
                frontend development, responsive design, and smooth user
                experience.
              </p>

              <button className="mt-6 px-5 py-3 rounded-xl bg-cyan-500 text-black font-semibold hover:bg-cyan-400 transition">
                View Project
              </button>
            </div>
          </div>
        </div>
      </section>

      {/* Contact Section */}
      <section className="max-w-7xl mx-auto px-6 py-24">
        <div className="bg-gradient-to-r from-cyan-500/10 to-blue-500/10 border border-white/10 rounded-[2rem] p-10 lg:p-16 text-center">
          <h2 className="text-4xl lg:text-5xl font-bold">
            Let's Connect 🚀
          </h2>

          <p className="text-gray-300 mt-6 text-lg max-w-2xl mx-auto leading-8">
            I’m always open to collaborating on innovative projects,
            contributing to open source, and exploring exciting opportunities
            in technology.
          </p>

          <div className="flex flex-wrap justify-center gap-5 mt-10">
            <a
              href="mailto:atulyadav91611@gmail.com"
              className="px-7 py-4 rounded-2xl bg-cyan-500 hover:bg-cyan-400 transition font-semibold text-black"
            >
              Email Me
            </a>

            <a
              href="https://atulyadav12135.github.io/Portfolio/"
              target="_blank"
              className="px-7 py-4 rounded-2xl border border-white/20 hover:border-cyan-400 hover:text-cyan-400 transition"
            >
              Visit Portfolio
            </a>
          </div>
        </div>
      </section>

      {/* Footer */}
      <footer className="border-t border-white/10 py-8 text-center text-gray-500 text-sm">
        © 2026 ATUL YADAV • Designed with React & Tailwind CSS
      </footer>
    </div>
  );
}

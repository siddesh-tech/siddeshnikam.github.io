# siddeshnikam.github.io
import React from "react";

export default function Portfolio() {
  return (
    <div className="p-6 max-w-4xl mx-auto font-sans">
      <h1 className="text-4xl font-bold mb-4">Siddesh Mahesh Nikam</h1>

      <section className="mb-6">
        <h2 className="text-2xl font-semibold">About Me</h2>
        <p className="mt-2 text-gray-700">
          I am Siddesh Mahesh Nikam, an aspiring software developer passionate about Java
          development, cloud computing, and modern technologies like AI and Machine Learning.
          With hands-on experience in project simulations and strong academic roots, I thrive on
          building scalable and efficient software solutions.
        </p>
      </section>

      <section className="mb-6">
        <h2 className="text-2xl font-semibold">Education</h2>
        <ul className="mt-2 text-gray-700 list-disc ml-6">
          <li><strong>B.Tech in Computer Engineering</strong> – Sandip Institute of Technology and Research Centre (Graduating 2027)</li>
          <li>12th Grade – Chhatrapati Shivaji Preparatory High School</li>
          <li>10th Grade – St. Lawrence High School</li>
        </ul>
      </section>

      <section className="mb-6">
        <h2 className="text-2xl font-semibold">Work Experience</h2>
        <p className="mt-2 text-gray-700">
          Participated in <span className="font-bold text-blue-600">Forage Virtual Job Simulation Programs</span>, gaining real-world exposure in:
        </p>
        <ul className="list-disc ml-6 text-gray-700">
          <li>Software Engineering at JPMorgan Chase & Co.</li>
          <li>Technology Consulting at Accenture</li>
          <li>Data Analytics at KPMG</li>
          <li>AI & ML Projects by AWS</li>
        </ul>
        <p className="mt-2 text-gray-700">
          These programs allowed me to simulate industry roles, solve real business problems, and develop
          technical and soft skills in a practical environment.
        </p>
      </section>

      <section className="mb-6">
        <h2 className="text-2xl font-semibold">Key Skills & Technologies</h2>
        <ul className="list-disc ml-6 text-gray-700">
          <li>Programming Languages: Java, JavaScript, Python</li>
          <li>Frameworks: Spring Boot, React (basic), Node.js</li>
          <li>Tools & Platforms: Git, VS Code, IntelliJ, Gradle</li>
          <li>Cloud & DevOps: AWS (basic), GitHub Actions</li>
          <li>Database: MySQL, MongoDB</li>
          <li>Soft Skills: Teamwork, Communication, Problem-Solving</li>
        </ul>
      </section>

      <section className="mb-6">
        <h2 className="text-2xl font-semibold">Certifications</h2>
        <ul className="list-disc ml-6 text-gray-700">
          <li>AWS Leadership Essentials</li>
          <li>Introduction to Machine Learning</li>
          <li>AI for Everyone</li>
          <li><strong>Forage Job Simulation Certificates</strong> (JPMorgan, Accenture, KPMG, AWS)</li>
        </ul>
      </section>

      <section className="mb-6">
        <h2 className="text-2xl font-semibold">Contact</h2>
        <ul className="mt-2 text-gray-700">
          <li>Email: siddeshnikam06@gmail.com</li>
          <li>Phone: +91 9975842005</li>
          <li>LinkedIn: <a href="https://www.linkedin.com/in/siddesh-nikam-3a95282a5" className="text-blue-600 underline">View Profile</a></li>
          <li>Location: Nashik, Maharashtra, India</li>
        </ul>
      </section>
    </div>
  );
}

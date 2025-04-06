# deepsea-alert
import React from 'react';
import { Waves as Wave, Fish, AlertTriangle, Droplets, ThermometerSun, Trash2, Github } from 'lucide-react';

function App() {
  return (
    <div className="min-h-screen bg-gradient-to-b from-blue-900 via-blue-800 to-blue-700">
      {/* Hero Section */}
      <header className="relative h-screen flex items-center justify-center text-white">
        <div className="absolute inset-0 bg-black/30"></div>
        <div className="relative z-10 max-w-4xl mx-auto text-center px-4">
          <h1 className="text-6xl font-bold mb-6">Deep Sea Migration Crisis</h1>
          <p className="text-xl mb-8">A Google Solution Challenge Project addressing the unprecedented migration of deep-sea creatures to surface waters</p>
          <Wave className="mx-auto w-16 h-16 animate-bounce" />
        </div>
      </header>

      {/* Problem Statement */}
      <section className="py-20 bg-white">
        <div className="max-w-6xl mx-auto px-4">
          <h2 className="text-4xl font-bold text-center mb-16 text-blue-900">The Rising Crisis</h2>
          <div className="grid md:grid-cols-3 gap-8">
            <div className="bg-blue-50 p-8 rounded-lg text-center">
              <ThermometerSun className="w-12 h-12 mx-auto mb-4 text-red-500" />
              <h3 className="text-xl font-semibold mb-4">Ocean Warming</h3>
              <p>Rising temperatures forcing deep-sea species to seek cooler waters</p>
            </div>
            <div className="bg-blue-50 p-8 rounded-lg text-center">
              <Droplets className="w-12 h-12 mx-auto mb-4 text-blue-500" />
              <h3 className="text-xl font-semibold mb-4">Oxygen Depletion</h3>
              <p>Decreasing oxygen levels in deep waters causing mass migration</p>
            </div>
            <div className="bg-blue-50 p-8 rounded-lg text-center">
              <Trash2 className="w-12 h-12 mx-auto mb-4 text-gray-500" />
              <h3 className="text-xl font-semibold mb-4">Pollution Impact</h3>
              <p>Deep-sea pollution disrupting natural habitats</p>
            </div>
          </div>
        </div>
      </section>

      {/* Solution Section */}
      <section className="py-20 bg-blue-900 text-white">
        <div className="max-w-6xl mx-auto px-4">
          <h2 className="text-4xl font-bold text-center mb-16">Our Solution</h2>
          <div className="grid md:grid-cols-2 gap-12 items-center">
            <div>
              <img 
                src="https://images.unsplash.com/photo-1551244072-5d12893278ab?auto=format&fit=crop&w=800&q=80" 
                alt="Deep sea monitoring system" 
                className="rounded-lg shadow-xl"
              />
            </div>
            <div>
              <h3 className="text-2xl font-semibold mb-6">AI-Powered Monitoring System</h3>
              <ul className="space-y-4">
                <li className="flex items-center gap-3">
                  <Fish className="w-6 h-6 text-blue-400" />
                  <span>Real-time tracking of deep-sea species migration</span>
                </li>
                <li className="flex items-center gap-3">
                  <AlertTriangle className="w-6 h-6 text-yellow-400" />
                  <span>Early warning system for ecosystem disruption</span>
                </li>
                <li className="flex items-center gap-3">
                  <Wave className="w-6 h-6 text-blue-400" />
                  <span>Ocean temperature and chemistry monitoring</span>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </section>

      {/* Call to Action */}
      <section className="py-20 bg-gradient-to-r from-blue-800 to-blue-900 text-white">
        <div className="max-w-4xl mx-auto text-center px-4">
          <h2 className="text-4xl font-bold mb-8">Join Our Mission</h2>
          <p className="text-xl mb-8">Help us protect our ocean's ecosystems and understand this unprecedented migration</p>
          <div className="flex justify-center gap-4">
            <a 
              href="https://github.com/yourusername/deep-sea-migration"
              target="_blank"
              rel="noopener noreferrer"
              className="flex items-center gap-2 bg-white text-blue-900 px-8 py-3 rounded-full font-semibold hover:bg-blue-50 transition-colors"
            >
              <Github className="w-5 h-5" />
              View on GitHub
            </a>
            <a 
              href="https://deep-sea-migration-mvp.demo.com"
              target="_blank"
              rel="noopener noreferrer"
              className="bg-blue-600 text-white px-8 py-3 rounded-full font-semibold hover:bg-blue-700 transition-colors"
            >
              Try MVP Demo
            </a>
          </div>
        </div>
      </section>

      {/* Footer */}
      <footer className="bg-blue-950 text-white py-8">
        <div className="max-w-6xl mx-auto px-4 text-center">
          <p>© 2025 Deep Sea Migration Project | Google Solution Challenge</p>
        </div>
      </footer>
    </div>
  );
}

export default App;

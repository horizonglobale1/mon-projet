import React from 'react';
import { Plane, Car, Code, ChevronRight, Phone, Mail, MapPin } from 'lucide-react';

function App() {
  return (
    <div className="min-h-screen bg-white">
      {/* Hero Section */}
      <header className="bg-gradient-to-r from-blue-900 to-blue-700 text-white">
        <nav className="container mx-auto px-6 py-4 flex justify-between items-center">
          <div className="flex items-center space-x-4">
            <div className="bg-white p-2 rounded-full">
              <img 
                src="https://imgur.com/a/yqVU8S8" 
                alt="HORIZON GLOBALE Logo" 
                className="h-16 w-16 object-contain"
              />
            </div>
            <span className="text-2xl font-bold">HORIZON GLOBALE</span>
          </div>
          <div className="hidden md:flex space-x-8">
            <a href="#services" className="hover:text-blue-200">Services</a>
            <a href="#about" className="hover:text-blue-200">À propos</a>
            <a href="#contact" className="hover:text-blue-200">Contact</a>
          </div>
        </nav>
        
        <div className="container mx-auto px-6 py-20">
          <h1 className="text-5xl font-bold mb-4">Votre Partenaire pour voyager, exporter et apprendre </h1>
          <p className="text-xl mb-8">Solutions complètes pour les visas Schengen, l'exportation de véhicules, le développement web, et des formations pluridisplinaire adapté à vos demandes</p>
          <a href="#contact" className="bg-white text-blue-900 px-8 py-3 rounded-full font-semibold hover:bg-blue-100 transition duration-300">
            Contactez-nous
          </a>
        </div>
      </header>

      {/* Services Section */}
      <section id="services" className="py-20 bg-gray-50">
        <div className="container mx-auto px-6">
          <h2 className="text-3xl font-bold text-center mb-16">Nos Services</h2>
          <div className="grid md:grid-cols-3 gap-12">
            <div className="bg-white p-8 rounded-lg shadow-lg">
              <Plane className="h-12 w-12 text-blue-700 mb-4" />
              <h3 className="text-xl font-semibold mb-4">Visas Schengen</h3>
              <p className="text-gray-600 mb-4">Accompagnement personnalisé pour l'obtention de visas de courte et longue durée dans l'espace Schengen.</p>
              <a href="#contact" className="flex items-center text-blue-700 hover:text-blue-900">
                En savoir plus <ChevronRight className="h-4 w-4 ml-2" />
              </a>
            </div>
            
            <div className="bg-white p-8 rounded-lg shadow-lg">
              <Car className="h-12 w-12 text-blue-700 mb-4" />
              <h3 className="text-xl font-semibold mb-4">Export de Véhicules</h3>
              <p className="text-gray-600 mb-4">Service d'achat et d'exportation de véhicules de toutes catégories selon vos besoins spécifiques.</p>
              <a href="#contact" className="flex items-center text-blue-700 hover:text-blue-900">
                En savoir plus <ChevronRight className="h-4 w-4 ml-2" />
              </a>
            </div>
            
            <div className="bg-white p-8 rounded-lg shadow-lg">
              <Code className="h-12 w-12 text-blue-700 mb-4" />
              <h3 className="text-xl font-semibold mb-4">Création Web</h3>
              <p className="text-gray-600 mb-4">Développement de sites web professionnels pour donner une présence en ligne à votre entreprise.</p>
              <a href="#contact" className="flex items-center text-blue-700 hover:text-blue-900">
                En savoir plus <ChevronRight className="h-4 w-4 ml-2" />
              </a>
            </div>
          </div>
        </div>
      </section>

      {/* About Section */}
      <section id="about" className="py-20">
        <div className="container mx-auto px-6">
          <div className="max-w-3xl mx-auto text-center">
            <h2 className="text-3xl font-bold mb-8">À Propos d'HORIZON GLOBALE</h2>
            <p className="text-gray-600 mb-6">
              HORIZON GLOBALE est votre partenaire de confiance pour concrétiser vos projets internationaux. 
              Notre expertise couvre l'ensemble des démarches liées à l'immigration dans l'espace Schengen, 
              l'exportation de véhicules et la création de solutions web innovantes.
            </p>
            <p className="text-gray-600">
              Notre équipe multilingue s'engage à vous offrir un service personnalisé et professionnel 
              pour garantir la réussite de vos projets.
            </p>
          </div>
        </div>
      </section>

      {/* Contact Section */}
      <section id="contact" className="py-20 bg-gray-50">
        <div className="container mx-auto px-6">
          <h2 className="text-3xl font-bold text-center mb-16">Contactez-nous</h2>
          <div className="max-w-4xl mx-auto grid md:grid-cols-2 gap-8">
            <div className="bg-white p-8 rounded-lg shadow-lg">
              <h3 className="text-xl font-semibold mb-6">Nos Coordonnées</h3>
              <div className="space-y-4">
                <div className="flex items-center">
                  <Phone className="h-5 w-5 text-blue-700 mr-4" />
                  <span>+39 3512368628</span>
                </div>
                <div className="flex items-center">
                  <Mail className="h-5 w-5 text-blue-700 mr-4" />
                  <span>horizonglobale@gamail.com</span>
                </div>
                <div className="flex items-center">
                  <MapPin className="h-5 w-5 text-blue-700 mr-4" />
                  <span>Bergamo, Italie</span>
                </div>
              </div>
            </div>
            <div className="bg-white p-8 rounded-lg shadow-lg">
              <h3 className="text-xl font-semibold mb-6">Horaires d'Ouverture</h3>
              <div className="space-y-2">
                <p>Lundi - Vendredi: 9:30h - 18h00</p>
                <p>Samedi: Sur rendez-vous</p>
                <p>Dimanche: Fermé</p>
              </div>
            </div>
          </div>
        </div>
      </section>

      {/* Footer */}
      <footer className="bg-blue-900 text-white py-8">
        <div className="container mx-auto px-6 text-center">
          <div className="flex items-center justify-center space-x-2 mb-4">
            <div className="bg-white p-2 rounded-full">
              <img 
                src="https://i.imgur.com/your-new-image-id.png" 
                alt="HORIZON GLOBALE Logo" 
                className="h-10 w-10 object-contain"
              />
            </div>
            <span className="text-xl font-bold">HORIZON GLOBALE</span>
          </div>
          <p className="text-blue-200">© {new Date().getFullYear()} HORIZON GLOBALE. Tous droits réservés.</p>
        </div>
      </footer>
    </div>
  );
}

export default App;

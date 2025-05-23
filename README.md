import { Card } from "@/components/ui/card"; import { Sparkles } from "lucide-react";

export default function RudraPage() { return ( <div className="min-h-screen bg-gradient-to-br from-blue-100 via-white to-blue-50 text-gray-800 font-sans"> {/* Hero Section */} <header className="text-center py-20"> <div className="text-6xl font-extrabold tracking-wide text-blue-600">RUDRA</div> <div className="text-lg text-gray-500 mt-3">The Silent Force Within</div> <div className="flex justify-center mt-6"> <div className="bg-blue-200 p-4 rounded-full shadow-lg"> <Sparkles className="h-10 w-10 text-blue-700" /> </div> </div> </header>

{/* About Section */}
  <section className="max-w-3xl mx-auto px-6 py-10">
    <Card className="p-6 shadow-lg rounded-2xl bg-white">
      <h2 className="text-2xl font-semibold mb-3 text-blue-700">Who is Rudra?</h2>
      <p className="text-gray-700 leading-relaxed">
        Rudra is a serene embodiment of strength and self-awareness. Beyond appearance or words, Rudra is an idea—a presence that influences with calm clarity and mindful resolve.
      </p>
    </Card>
  </section>

  {/* Philosophy Section */}
  <section className="max-w-4xl mx-auto px-6 py-10">
    <Card className="p-6 shadow-lg rounded-2xl bg-blue-100">
      <h2 className="text-2xl font-semibold mb-3 text-blue-800">Philosophy</h2>
      <p className="text-gray-700 leading-relaxed">
        True strength lies in tranquility. Rudra stands between power and peace—a guide that observes without disturbance and acts with inner conviction.
      </p>
    </Card>
  </section>

  {/* Quote Section */}
  <section className="text-center py-16 px-6 bg-white">
    <blockquote className="text-2xl italic text-blue-600 max-w-2xl mx-auto">
      "Stillness is not the absence of energy, it is the presence of inner strength."
    </blockquote>
  </section>

  {/* Footer */}
  <footer className="text-center text-sm text-gray-500 py-6">
    &copy; 2025 Rudra Essence. Designed with calm and clarity.
  </footer>
</div>

); }


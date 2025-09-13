import { Button } from "@/components/ui/button"; import { Card, CardContent } from "@/components/ui/card"; import { motion } from "framer-motion";

export default function Home() { return ( <div className="min-h-screen bg-gradient-to-b from-pink-50 to-white text-gray-800"> {/* Hero Section */} <section className="text-center py-20 px-6"> <motion.h1 initial={{ opacity: 0, y: -20 }} animate={{ opacity: 1, y: 0 }} transition={{ duration: 0.8 }} className="text-4xl md:text-6xl font-bold mb-4" > IndianWed </motion.h1> <motion.p initial={{ opacity: 0 }} animate={{ opacity: 1 }} transition={{ delay: 0.3, duration: 0.8 }} className="text-lg md:text-2xl mb-6" > Celebrate Love. Experience India. </motion.p> <Button size="lg" className="rounded-2xl shadow-lg"> Explore Experiences </Button> </section>

{/* How It Works */}
  <section className="py-16 px-6 bg-white">
    <h2 className="text-3xl font-semibold text-center mb-10">How It Works</h2>
    <div className="grid md:grid-cols-3 gap-8 max-w-5xl mx-auto">
      {[
        {
          title: "Pick an Event",
          desc: "Choose from haldi, mehendi, sangeet, baraat, or ceremony.",
        },
        {
          title: "Book & Verify",
          desc: "Secure your spot with ID verification & etiquette guide.",
        },
        {
          title: "Celebrate Respectfully",
          desc: "Join with local chaperones ensuring safety & dignity.",
        },
      ].map((step, i) => (
        <Card key={i} className="rounded-2xl shadow-md">
          <CardContent className="p-6 text-center">
            <h3 className="text-xl font-bold mb-2">{step.title}</h3>
            <p className="text-gray-600">{step.desc}</p>
          </CardContent>
        </Card>
      ))}
    </div>
  </section>

  {/* Sample Experience */}
  <section className="py-16 px-6 bg-pink-50">
    <h2 className="text-3xl font-semibold text-center mb-10">Sample Experience</h2>
    <div className="max-w-md mx-auto">
      <Card className="rounded-2xl shadow-md">
        <CardContent className="p-6">
          <h3 className="text-xl font-bold mb-2">Haldi Ceremony in Jaipur</h3>
          <p className="text-gray-600 mb-4">
            Duration: 3 Hours | Price: ₹5,999 | Includes attire guide, food, and chaperone.
          </p>
          <Button className="w-full rounded-2xl">Book Now</Button>
        </CardContent>
      </Card>
    </div>
  </section>

  {/* Footer */}
  <footer className="py-6 text-center text-gray-500 text-sm">
    © {new Date().getFullYear()} IndianWed. All rights reserved.
  </footer>
</div>

); }


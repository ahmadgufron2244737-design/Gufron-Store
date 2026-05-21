export default function GufronJokiWebsite() { const services = [ { title: "Joki Ranked", desc: "Push rank cepat, aman, dan terpercaya.", }, { title: "Joki Classic", desc: "Naik winrate dengan permainan profesional.", }, { title: "Joki Event", desc: "Bantu selesaikan event dan misi game.", }, ];

return ( <div className="min-h-screen bg-black text-white font-sans"> <header className="border-b border-gray-800"> <div className="max-w-6xl mx-auto px-6 py-5 flex items-center justify-between"> <h1 className="text-3xl font-bold tracking-wide">Gufron</h1> <a
href="https://wa.me/6282395677193"
target="_blank"
className="bg-white text-black px-5 py-2 rounded-2xl font-semibold hover:scale-105 transition"
> Hubungi </a> </div> </header>

<section className="max-w-6xl mx-auto px-6 py-24 text-center">
    <h2 className="text-5xl md:text-7xl font-bold leading-tight">
      Jasa Joki Game
      <span className="block text-gray-400">Cepat • Aman • Trusted</span>
    </h2>

    <p className="mt-8 text-gray-300 max-w-2xl mx-auto text-lg">
      Gufron menyediakan layanan joki game profesional dengan proses cepat,
      aman, dan harga terjangkau.
    </p>

    <div className="mt-10 flex justify-center gap-4 flex-wrap">
      <a
        href="https://wa.me/6282395677193"
        target="_blank"
        className="bg-white text-black px-8 py-4 rounded-2xl text-lg font-bold hover:scale-105 transition"
      >
        Pesan Sekarang
      </a>

      <a
        href="#layanan"
        className="border border-white px-8 py-4 rounded-2xl text-lg hover:bg-white hover:text-black transition"
      >
        Lihat Layanan
      </a>
    </div>
  </section>

  <section id="layanan" className="max-w-6xl mx-auto px-6 py-16">
    <h3 className="text-4xl font-bold text-center mb-14">Layanan</h3>

    <div className="grid md:grid-cols-3 gap-8">
      {services.map((item, index) => (
        <div
          key={index}
          className="bg-zinc-900 border border-zinc-800 rounded-3xl p-8 hover:border-white transition shadow-xl"
        >
          <h4 className="text-2xl font-bold mb-4">{item.title}</h4>
          <p className="text-gray-400 leading-relaxed">{item.desc}</p>
        </div>
      ))}
    </div>
  </section>

  <section className="max-w-4xl mx-auto px-6 py-20 text-center">
    <div className="bg-zinc-900 border border-zinc-800 rounded-3xl p-10 shadow-2xl">
      <h3 className="text-4xl font-bold">Order via WhatsApp</h3>

      <p className="text-gray-400 mt-4 text-lg">
        Klik tombol di bawah untuk langsung memesan jasa joki.
      </p>

      <a
        href="https://wa.me/6282395677193"
        target="_blank"
        className="inline-block mt-8 bg-white text-black px-10 py-4 rounded-2xl text-lg font-bold hover:scale-105 transition"
      >
        Chat WhatsApp
      </a>
    </div>
  </section>

  <footer className="border-t border-gray-800 py-8 text-center text-gray-500">
    © 2026 Gufron Joki Game. All rights reserved.
  </footer>
</div>

); }

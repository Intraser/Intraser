## Hi there 👋

<!--
**Intraser/Intraser** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
// INSTRUCTIONS:
// 1) Replace '/assets/logo.png' with the logo file you will upload (or keep same name).
// 2) Replace videoSrc with the video file URL provided by Thiago.
// 3) Replace background images (bgGradient and sectionIllustrations) with final images if you want.
// 4) This component uses Tailwind CSS. Ensure Tailwind is configured in your project.


export default function IntraserLandingPage() {
const videoSrc = "/assets/thiago-video.mp4"; // <- replace with actual video file path


return (
<div className="min-h-screen antialiased text-gray-800 bg-gradient-to-b from-white via-[#E6F0EA] to-[#EAF6FF]">
{/* Top fixed menu */}
<header className="fixed top-0 left-0 right-0 bg-white/60 backdrop-blur-sm z-50">
<nav className="max-w-6xl mx-auto flex items-center justify-between py-4 px-6">
<div className="flex items-center gap-3">
<img src="/assets/logo.png" alt="INTRASER logo" className="h-10 w-auto" />
<span className="sr-only">INTRASER - Mind & Soul Balance</span>
</div>
<ul className="hidden md:flex items-center gap-6 text-sm font-medium">
<li><a href="#inicio" className="hover:underline">Início</a></li>
<li><a href="#terapias" className="hover:underline">Terapias</a></li>
<li><a href="#ebook" className="hover:underline">Ebook</a></li>
<li><a href="#loja" className="hover:underline">Loja</a></li>
<li><a href="#depoimentos" className="hover:underline">Depoimentos</a></li>
<li><a href="#contato" className="hover:underline">Contato</a></li>
</ul>
<div className="flex items-center gap-3">
<a href="#agendar" className="hidden md:inline-block px-4 py-2 rounded-2xl bg-green-700 text-white text-sm">Agendar</a>
<button className="md:hidden p-2 rounded-lg ring-1 ring-gray-200">Menu</button>
</div>
</nav>
</header>


<main className="pt-24">
{/* Hero / Comece sua Transformação Hoje */}
<section id="inicio" className="max-w-6xl mx-auto px-6 py-12 lg:py-20">
<div className="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
<div>
<h1 className="text-3xl md:text-4xl font-extrabold leading-tight">
Comece sua Transformação Hoje
</h1>
<p className="mt-4 text-gray-700 max-w-xl">
Cuidar da mente é um ato de amor próprio. Quando negligenciamos nossas emoções,
abrimos espaço para doenças físicas, esgotamento e pensamentos negativos. A transformação
começa ao olhar para dentro e decidir se libertar do que nos prende. Transforme sua dor em
força e sua mente em seu maior aliado.
</p>


<div className="mt-6 flex flex-wrap gap-3">
<a href="#agendar" className="px-6 py-3 rounded-full bg-green-700 text-white font-semibold shadow-sm">Agendar minha sessão de equilíbrio mental</a>
<a href="#ebook" className="px-4 py-3 rounded-full border border-gray-200 text-sm">Baixar Ebook Gratuito</a>
</div>


<ul className="mt-8 text-sm text-gray-600 space-y-2">
<li>➡ Terapia TRG • Terapia Motivacional • Terapia Vibracional • Massoterapia</li>
<li>➡ Acesso online — Atendimentos remotos e presenciais (personalize conforme necessário)</li>
</ul>
</div>


<div className="bg-white/60 rounded-2xl p-4 shadow-lg">
<div className="aspect-video rounded-xl overflow-hidden bg-white flex items-center justify-center">
{/* Video placeholder */}
<video src={videoSrc} controls className="w-full h-full object-cover">Seu navegador não suporta vídeo.</video>
</div>
<p className="mt-3 text-center text-sm text-gray-600">Cuidar da mente é um ato de amor — mensagem de Thiago.</p>
</div>
</div>
</section>

<script setup>
import { ref } from 'vue'
import mypicport from './assets/mypicport.jpg'
import cardbotcare from './assets/cardbotcare.png'
import botnoi from './assets/botnoi.png'

</script>

<template>
  <nav class="fixed top-0 w-full z-50 glass-nav">
      <div class="max-w-7xl text-left px-10 h-20 flex justify-between items-center">
          <span class="font-headline font-black text-2xl tracking-tighter text-on-background uppercase">PORTFOLIO</span>
          <div class=" md: items-center space-x-12">
              <a class="font-headline text-sm font-extrabold tracking-tight text-primary border-b-2 border-primary pb-1" href="#">Home</a>
              <a class="font-headline text-sm font-bold tracking-tight text-on-surface-variant hover:text-on-surface transition-colors duration-300" href="#about">About Me</a>
              <a class="font-headline text-sm font-bold tracking-tight text-on-surface-variant hover:text-on-surface transition-colors duration-300" href="#contact">Contact</a>
              <a class="font-headline text-sm font-bold tracking-tight text-on-surface-variant hover:text-on-surface transition-colors duration-300" href="#work">My Projects</a>
              
            <!--<div class="relative group">
                    <button class="font-headline text-sm font-bold tracking-tight text-on-surface-variant group-hover:text-primary transition-colors duration-300 flex items-center gap-1 pb-1">
            
                <span class="material-symbols-outlined text-sm transition-transform duration-300 group-hover:rotate-180">expand_more</span>
            </button>-->
        
            <!--<div class="absolute left-0 top-full mt-2 w-48 bg-surface-container-lowest border border-outline-variant/20 rounded-xl shadow-xl opacity-0 invisible group-hover:opacity-100 group-hover:visible transition-all duration-300 transform origin-top -translate-y-2 group-hover:translate-y-0 flex flex-col py-2 z-50">
                <a href="#" class="px-5 py-2.5 font-body text-sm text-on-surface-variant hover:bg-surface-container-low hover:text-primary transition-colors">Branding Design</a>
                <a href="#" class="px-5 py-2.5 font-body text-sm text-on-surface-variant hover:bg-surface-container-low hover:text-primary transition-colors">Web Development</a>
                <a href="#" class="px-5 py-2.5 font-body text-sm text-on-surface-variant hover:bg-surface-container-low hover:text-primary transition-colors">Digital Strategy</a>
            </div>
            </div>-->

          </div>
          <!--<button class="bg-gradient-to-br from-primary to-primary-container text-on-primary px-8 py-3 rounded-xl font-label text-[10px] font-bold uppercase tracking-widest hover:shadow-[0_20px_40px_rgba(0,65,200,0.15)] transition-all active:scale-95">
              Contact
          </button>-->
      </div>
  </nav>

  <main class="pt-20">
      <section class="relative min-h-auto flex items-center px-10 max-w-7xl mx-auto overflow-visible">
          <div class="grid grid-cols-12 gap-8 items-center w-full">
              <div class="col-span-12 lg:col-span-7 z-10">
                  <span class="font-label text-[10px] font-bold uppercase tracking-[0.2em] text-left text-primary mb-6 block">me & my ux/ui portfolio</span>
                  <h1 class="font-headline text-left text-[3.5rem] lg:text-[5rem] font-extrabold leading-[1.05] tracking-[-0.03em] text-on-surface mb-0">
                        HI! 
                        <span class="font-body text-[2rem] text-on-surface-variant font-normal">
                            I'm guy
                        </span>
                    </h1>
                  <h3 class="font-headline text-left text-[2rem] lg:text-[2.5rem] font-semibold leading-[1.05] tracking-[-0.03em] text-on-surface mb-6">
                          Thapanapong Mungsuwan
                    </h3>


                  <p class="font-body text-left text-lg text-on-surface-variant max-w-lg mb-10 leading-relaxed">
                      Hello, you can call me Guy. My journey as a UX/UI designer began during my university studies. There, I learned about user research, workflows, and design processes aimed at solving real user problems. It was exciting to create solutions that could genuinely improve user experiences.
                  </p>
                  <div class="flex items-center gap-6">
                        <a href="#work" class="bg-gradient-to-br from-primary to-primary-container text-on-primary px-10 py-5 rounded-xl font-label text-xs font-bold uppercase tracking-widest hover:shadow-[0_25px_50px_rgba(0,65,200,0.2)] transition-all inline-block text-center">
                            View My Work
                        </a> 
                    </div>
              </div>
              <div class="col-span-12 lg:col-span-5 relative mt-12 lg:mt-0">
                  <div class="relative w-full aspect-[4/5] bg-surface-container-low rounded-xl overflow-hidden shadow-2xl">
                      <img alt="My Profile Picture" class="..." :src="mypicport" />
                      <div class="absolute inset-0 bg-primary/5 mix-blend-multiply"></div>
                  </div>
                  <!--<div class="absolute -bottom-8 -left-8 lg:-left-16 p-8 bg-surface-container-lowest/80 backdrop-blur-xl rounded-xl shadow-[0_40px_60px_rgba(28,27,27,0.04)] max-w-[280px]">
                      <p class="font-headline text-3xl font-black text-on-surface mb-1">08+</p>
                      <p class="font-label text-[10px] uppercase tracking-widest text-on-surface-variant">Years of Excellence in Design</p>
                  </div>-->
              </div>
          </div>
      </section>

      <!--<div class="w-full bg-surface-container-low py-12 overflow-hidden whitespace-nowrap">
          <div class="animate-marquee">
              <div class="flex gap-20">
                  <span class="font-headline text-4xl font-extrabold text-outline-variant/30 uppercase italic">Branding</span>
                  <span class="font-headline text-4xl font-extrabold text-outline-variant/30 uppercase italic">Curation</span>
                  <span class="font-headline text-4xl font-extrabold text-outline-variant/30 uppercase italic">Strategy</span>
                  <span class="font-headline text-4xl font-extrabold text-outline-variant/30 uppercase italic">Development</span>
                  <span class="font-headline text-4xl font-extrabold text-outline-variant/30 uppercase italic">Experience</span>
              </div>
              <div class="flex gap-20 ml-20">
                  <span class="font-headline text-4xl font-extrabold text-outline-variant/30 uppercase italic">Branding</span>
                  <span class="font-headline text-4xl font-extrabold text-outline-variant/30 uppercase italic">Curation</span>
                  <span class="font-headline text-4xl font-extrabold text-outline-variant/30 uppercase italic">Strategy</span>
                  <span class="font-headline text-4xl font-extrabold text-outline-variant/30 uppercase italic">Development</span>
                  <span class="font-headline text-4xl font-extrabold text-outline-variant/30 uppercase italic">Experience</span>
              </div>
          </div>
      </div>-->

      <section class="py-32 px-10 max-w-7xl mx-auto" id="about">
          <div class="mb-20">
              <span class="font-label text-[10px] font-bold uppercase tracking-[0.2em] text-primary mb-6 block">The Creative Journey</span>
              <h2 class="font-headline text-4xl lg:text-6xl font-extrabold tracking-tight text-on-surface text-left mb-8">Who am I ?  </h2>
              <div class="w-24 h-1.5 bg-primary"></div>
          </div>
          <div class="grid grid-cols-12 gap-16 text-left">
              <div class="col-span-12 lg:col-span-7">
                  <div class="mb-16">
                      <h3 class="font-headline text-2xl font-extrabold text-on-surface mb-6">Profile</h3>
                      <p class="font-body text-lg text-on-surface-variant leading-relaxed mb-6">
                          I’m a <span class="text-primary font-bold italic">UX/UI designer</span> who loves turning ideas into clean, easy-to-use experiences. I enjoy mixing creativity with logic—designing interfaces that not only look good but actually work.
                      </p>
                      <p class="font-body text-lg text-on-surface-variant leading-relaxed">
                          From building quirky physics-based games to exploring business ideas, I like solving real problems and making things feel simple for users. I’m especially interested in designing for everyday people—making digital experiences smoother, clearer, and more enjoyable. 
                      </p>
                  </div>
                  <div class="space-y-12">
                      <h3 class="font-headline text-2xl font-extrabold text-on-surface mb-8">Work Experience</h3>
                      <div class="mb-16 space-y-10">
                          <div class="flex-1 flex-row md:flex-col md:items-start gap-2 md:gap-6 group">
                              <span class="font-label text-xs font-bold uppercase tracking-widest text-primary min-w-[120px] pt-1">12/2025 — 04/2026.</span>
                              <div>
                                  <h4 class="font-headline text-xl font-bold text-on-surface mb-1 group-hover:text-primary transition-colors">Trainee UX/UI designer</h4>
                                  <p class="font-label text-[10px] uppercase tracking-widest text-on-surface-variant mb-3">IBOTNOI COMPANY LIMITED • bkk</p>
                                  <p class="font-body text-sm text-on-surface-variant leading-relaxed">Responsible for designing user interfaces and user experiences, including conducting usability testing, creating wireframes, and developing user flows.</p>
                              </div>
                          </div>
                          <!--<div class="flex flex-col md:flex-row md:items-start gap-2 md:gap-8 group border-t border-outline-variant/20 pt-10">
                              <span class="font-label text-xs font-bold uppercase tracking-widest text-on-surface-variant min-w-[120px] pt-1">2018 — 2021</span>
                              <div>
                                  <h4 class="font-headline text-xl font-bold text-on-surface mb-1 group-hover:text-primary transition-colors">Senior Product Designer</h4>
                                  <p class="font-label text-[10px] uppercase tracking-widest text-on-surface-variant mb-3">GALLERY INTERACTIVE • NYC</p>
                                  <p class="font-body text-sm text-on-surface-variant leading-relaxed">Defined the visual language for immersive digital art platforms. Focused on high-fidelity prototyping and custom grid-based layouts.</p>
                              </div>
                          </div>-->
                          <div class="flex-1 flex-row md:flex-col md:items-start gap-2 md:gap-8 group border-t border-outline-variant/20 pt-10">
                              <span class="font-label text-xs font-bold uppercase tracking-widest text-on-surface-variant min-w-[120px] pt-1">06/2566 - 08/2566</span>
                              <div>
                                  <h4 class="font-headline text-xl font-bold text-on-surface mb-1 group-hover:text-primary transition-colors">Waiter(Part - time)</h4>
                                  <p class="font-label text-[10px] uppercase tracking-widest text-on-surface-variant mb-3">The chocolate factory • bkk</p>
                                  <p class="font-body text-sm text-on-surface-variant leading-relaxed">responsible for serving food, clearing tables, and maintaining cleanliness within the establishment. Ensured a clean and organized environment while providing support to the service team.</p>
                              </div>
                          </div>
                      </div>
                  </div>
              </div>
              <div class="col-span-12 lg:col-span-5 flex flex-col gap-12">
                  <div class="relative group">
                      <div class="aspect-square bg-on-surface rounded-xl overflow-hidden p-12 flex flex-col justify-between">
                          <h3 class="font-headline text-2xl font-extrabold text-surface">Beyond the Canvas</h3>
                          <div class="space-y-8">
                              <div class="flex items-center gap-6 group/item">
                                  <div class="w-12 h-12 rounded-full border border-surface/20 flex items-center justify-center group-hover/item:bg-primary transition-colors">
                                      <span class="material-symbols-outlined text-surface">brush</span>
                                  </div>
                                  <div>
                                      <p class="font-headline font-bold text-surface">Doodling</p>
                                      <p class="font-label text-[10px] text-surface/50 uppercase tracking-widest">Freehand abstract sketching</p>
                                  </div>
                              </div>
                              <div class="flex items-center gap-6 group/item">
                                  <div class="w-12 h-12 rounded-full border border-surface/20 flex items-center justify-center group-hover/item:bg-primary transition-colors">
                                      <span class="material-symbols-outlined text-surface">coffee</span>
                                  </div>
                                  <div>
                                      <p class="font-headline font-bold text-surface">Coffee Curation</p>
                                      <p class="font-label text-[10px] text-surface/50 uppercase tracking-widest">Mastering the pour-over</p>
                                  </div>
                              </div>
                              <div class="flex items-center gap-6 group/item">
                                  <div class="w-12 h-12 rounded-full border border-surface/20 flex items-center justify-center group-hover/item:bg-primary transition-colors">
                                      <span class="material-symbols-outlined text-surface">sports_esports</span>
                                  </div>
                                  <div>
                                      <p class="font-headline font-bold text-surface">Play Games</p>
                                      <p class="font-label text-[10px] text-surface/50 uppercase tracking-widest">Strategy & Open World Exploration</p>
                                  </div>
                              </div>
                          </div>
                      </div>
                      <div class="absolute -top-4 -right-4 w-20 h-20 border-t-2 border-r-2 border-primary rounded-tr-xl -z-10"></div>
                  </div>
                  <!-- สกิล -->
                  <div class="bg-surface-container-low p-10 rounded-xl border border-outline-variant/10">
                      <h3 class="font-headline text-xl font-extrabold text-on-surface mb-8">Technical & Creative Skills</h3>
                      <div class="grid grid-cols-1 sm:grid-cols-2 gap-x-8 gap-y-6">
                          <div class="space-y-4">
                              <div class="flex items-center gap-3">
                                  <span class="w-1.5 h-1.5 rounded-full bg-primary"></span>
                                  <span class="text-sm font-headline font-bold">User Research</span>
                              </div>
                              <div class="flex items-center gap-3">
                                  <span class="w-1.5 h-1.5 rounded-full bg-primary"></span>
                                  <span class="text-sm font-headline font-bold">User centered design </span>
                              </div>
                              <div class="flex items-center gap-3">
                                  <span class="w-1.5 h-1.5 rounded-full bg-primary"></span>
                                  <span class="text-sm font-headline font-bold">UI Design</span>
                              </div>
                          </div>
                          <div class="space-y-4">
                              <div class="flex items-center gap-3">
                                  <span class="w-1.5 h-1.5 rounded-full bg-primary"></span>
                                  <span class="text-sm font-headline font-bold">Figma & Adobe(Ai, Ps)</span><!-- #FF9A00-->
                              </div>
                              <div class="flex items-center gap-3">
                                  <span class="w-1.5 h-1.5 rounded-full bg-primary"></span>
                                  <span class="text-sm font-headline font-bold">Grid Systems</span>
                              </div>
                              <div class="flex items-center gap-3">
                                  <span class="w-1.5 h-1.5 rounded-full bg-primary"></span>
                                  <span class="text-sm font-headline font-bold">Brand Identity</span>
                              </div>
                          </div>
                      </div>
                  </div>
              </div>
          </div>
      </section>

      <section class="py-8 px-10 max-w-7xl mx-auto bg-surface-container-lowest">
          <div class="flex flex-col md:flex-row justify-between items-end mb-16 gap-6">
              <div class="max-w-2xl">
        
                  <h2 class="font-headline text-4xl lg:text-5xl font-extrabold tracking-tight text-on-surface">Curated Works</h2>
              </div>
              <!-- <a class="font-label text-xs font-bold uppercase tracking-widest text-on-surface hover:text-primary transition-colors flex items-center gap-2 group" href="#">
                  View All Projects
                  <span class="material-symbols-outlined text-sm group-hover:translate-x-1 transition-transform">arrow_forward</span>
              </a>-->
          </div>
          <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-10" id="work">
              <div class="group">
                  <div class="relative aspect-[5/5] overflow-hidden rounded-xl bg-surface-container-low mb-6 p-8">
                    <img alt="cardbotcare" class="w-full h-full object-center object-cover grayscale group-hover:grayscale-0 group-hover:scale-105 transition-all duration-700 mix-blend-multiply" :src="cardbotcare" />
                    <div class="absolute inset-0 bg-on-surface/5 opacity-0 group-hover:opacity-100 transition-opacity"></div>
                </div>
                  <h3 class="font-headline text-xl font-extrabold text-on-surface mb-2">BotCare</h3>
                  <p class="font-body text-left text-sm text-on-surface-variant mb-6"> Conducted research and designed the user interface for an AI Voice application tailored to support elderly users.</p>
                  <button class="font-label text-[10px] font-bold uppercase tracking-[0.2em] text-primary hover:text-on-surface transition-colors flex items-center gap-2">
                      <a href="https://drive.google.com/file/d/1wAQXbJuyarXx5WNtxTKMNzBMo1amu4-V/view?usp=drive_link" target="_blank" class="...">View Project <span class="material-symbols-outlined text-xs">north_east</span></a>
                  </button>
                </div>

                <div class="group">
                  <div class="relative aspect-[5/5] overflow-hidden rounded-xl bg-surface-container-low mb-6 p-8">
                    <img alt="BotNoi" class="w-full h-full object-center object-cover grayscale group-hover:grayscale-0 group-hover:scale-105 transition-all duration-700 mix-blend-multiply" :src="botnoi" />
                    <div class="absolute inset-0 bg-on-surface/5 opacity-0 group-hover:opacity-100 transition-opacity"></div>
                </div>
                  <h3 class="font-headline text-xl font-extrabold text-on-surface mb-2">BotNoi</h3>
                  <p class="font-body text-left text-sm text-on-surface-variant mb-6"> Developed skills in UI design and UX research through real-world projects. Supported team members and contributed to user-centered design solutions.</p>
                  <button class="font-label text-[10px] font-bold uppercase tracking-[0.2em] text-primary hover:text-on-surface transition-colors flex items-center gap-2">
                      <a href="https://drive.google.com/file/d/1n4WVr_Ewy8RPKuMQt2PWhX8lz6NIETDX/view?usp=sharing" target="_blank" class="...">View Project <span class="material-symbols-outlined text-xs">north_east</span></a>
                  </button>
                </div>
              <!--<div class="group">
                  <div class="relative aspect-[4/5] overflow-hidden rounded-xl bg-surface-container-low mb-6">
                      <img alt="Digital Experience Project" class="w-full h-full object-cover grayscale group-hover:grayscale-0 group-hover:scale-105 transition-all duration-700" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAo5ABBo2PrFAciOnPJ1ia0dDPxzv5KR0gJy1VQuTcKsQHmuRX5VjhHotf9n6zbstEum5JyTZK8tAURi_okT2ce8F3vAe4-rq-NoZMrQ141BhueOQgASGw8voF7RaDzDOui0aA655R8iMpTQot266G0XV0v-Klq2_tiRL5v-4pOt1kKphRfd4o-qlF_2lSi5UqhJICY7qlgwhL-4oebAWM7VXdaccAmH_hFe5YmdlwZQlg20JuilLDVCzQjhlsmR5VPnqYe0zTkBBGT" />
                      <div class="absolute inset-0 bg-on-surface/5 opacity-0 group-hover:opacity-100 transition-opacity"></div>
                  </div>
                  <h3 class="font-headline text-xl font-extrabold text-on-surface mb-2">Digital Experience</h3>
                  <p class="font-body text-sm text-on-surface-variant mb-6">A immersive web sanctuary for architectural preservationists.</p>
                  <button class="font-label text-[10px] font-bold uppercase tracking-[0.2em] text-primary hover:text-on-surface transition-colors flex items-center gap-2">
                      View Project <span class="material-symbols-outlined text-xs">north_east</span>
                  </button>
              </div>
              <div class="group">
                  <div class="relative aspect-[4/5] overflow-hidden rounded-xl bg-surface-container-low mb-6">
                      <img alt="Editorial Design Project" class="w-full h-full object-cover grayscale group-hover:grayscale-0 group-hover:scale-105 transition-all duration-700" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCSPIh6QQDhazyIkHGiX-F-i1fnE4vvy_C5-bG32fcVroNxBSgOthKVsVRO-NnqI6wKGi77Gt7-gjzMd7cS3MxBijr3PEbTJaNlV4pEA2XuA3t7XQ48TF7SNdfgScmecZrmuoR0QhlH9YFbHpC6IsMC3Cyj4DwakpaqzzWWyekjjdhXUEowUUAD3I6_PxhItDKiI_hdkS3L5lnuYsl4UL0UdlRHr0xanC9wS4mVyZLqTtBwfeNAwZP5wIAMTU-3kKNYj65vJ6POKUvO" />
                      <div class="absolute inset-0 bg-on-surface/5 opacity-0 group-hover:opacity-100 transition-opacity"></div>
                  </div>
                  <h3 class="font-headline text-xl font-extrabold text-on-surface mb-2">Editorial Design</h3>
                  <p class="font-body text-sm text-on-surface-variant mb-6">Curated layout systems for biannual luxury lifestyle journals.</p>
                  <button class="font-label text-[10px] font-bold uppercase tracking-[0.2em] text-primary hover:text-on-surface transition-colors flex items-center gap-2">
                      View Project <span class="material-symbols-outlined text-xs">north_east</span>
                  </button>
              </div>-->
          </div>
      </section>
  </main>

  <footer class="w-full mt-10 px-4 md:px-0" id="contact">
    <div class="bg-[#0055FF] text-white rounded-3xl px-8 py-10 md:px-12 md:py-14 flex flex-col md:flex-row justify-between items-start md:items-center gap-10">

        <div class="flex flex-col items-start gap-4">
            <span class="font-headline font-bold text-lg text-white text-left tracking-wider">PORTFOLIO</span>
            <div class="flex flex-col gap-3">
                <h2 class="text-xl md:text-[2.75rem] text-white font-bold tracking-tight">Explore & Connect</h2>
                <div class="flex gap-6 md:gap-8 text-xl md:text-2xl mt-2 font-medium">
                    <a href="#work" class="hover:text-white/70 transition-colors duration-300">Project</a>
                    <a href="#about" class="hover:text-white/70 transition-colors duration-300">About</a>
                    <a href="#" class="hover:text-white/70 transition-colors duration-300">Resume</a>
                </div>
            </div>
        </div>
          
        <div class="flex flex-row flex-wrap md:flex-nowrap gap-6 md:gap-8 text-xs md:text-sm font-semibold tracking-[0.15em] uppercase">
            <a href="#" class="hover:text-white/70 transition-colors duration-300">LinkedIn</a>
            <a href="#" class="hover:text-white/70 transition-colors duration-300">Dribbble</a>
            <a href="#" class="hover:text-white/70 transition-colors duration-300">Instagram</a>
            <a href="mailto:thapanapong@gmail.com" class="hover:text-white/70 transition-colors duration-300">Email</a>
        </div>

    </div>
</footer>
</template>

<style>
.material-symbols-outlined {
    font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
}
.glass-nav {
    background: rgba(252, 249, 248, 0.7);
    backdrop-filter: blur(20px);
}
.text-glow {
    text-shadow: 0 0 20px rgba(0, 65, 200, 0.1);
}
@keyframes marquee {
    0% { transform: translateX(0); }
    100% { transform: translateX(-50%); }
}
.animate-marquee {
    display: flex;
    width: 200%;
    animation: marquee 30s linear infinite;
}
</style>
    <!-- work project section starts -->
    <section class="projects-section" id="projects">

        <h2 class="heading"><i class="fas fa-laptop-code"></i> Projects <span>Made</span></h2>


        <div class="projects-container animate-project" id="projects-list">

            <!-- Website Codetech.id -->
            <div class="project-card">
                <img draggable="false" src="./assets/images/projects/codetech.png" alt="Toko eCommerce" />
                <div class="content">
                    <div class="project-title">
                        <h3>Website codetech.id</h3>
                    </div>
                    <div class="project-description">
                        <p>Website resmi Codetech.id perusahaan digital berbasis teknologi yang menyediakan layanan
                            pembuatan website, sistem informasi, dan edukasi. </p>
                        <div class="project-buttons">
                            <a href="https://codetech.id" class="btn" target="_blank"><i class="fas fa-eye"></i>
                                View</a>
                            <a href="https://github.com/asepsurahman03/codetech" class="btn" target="_blank">Code <i
                                    class="fas fa-code"></i></a>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Website Saveedu -->
            <div class="project-card">
                <img draggable="false" src="./assets/images/projects/saveedu.png" alt="Saveedu" />
                <div class="content">
                    <div class="project-title">
                        <h3>Website Saveedu</h3>
                    </div>
                    <div class="project-description">
                        <p>Website resmi Saveedu untuk layanan kebutuhan joki game Mobile Legends.</p>
                        <div class="project-buttons">
                            <a href="https://codejoki-id.vercel.app" class="btn" target="_blank"><i
                                    class="fas fa-eye"></i> View</a>
                            <a href="https://github.com/asepsurahman03/joki-topup" class="btn" target="_blank">Code <i
                                    class="fas fa-code"></i></a>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Website Codejoki.id -->
            <div class="project-card">
                <img draggable="false" src="./assets/images/projects/codejoki.png" alt="Codejoki.id" />
                <div class="content">
                    <div class="project-title">
                        <h3>Website Codejoki.id</h3>
                    </div>
                    <div class="project-description">
                        <p>Website resmi Codejoki.id untuk layanan kebutuhan joki game Mobile Legends.</p>
                        <div class="project-buttons">
                            <a href="https://codejoki-id.vercel.app" class="btn" target="_blank"><i
                                    class="fas fa-eye"></i> View</a>
                            <a href="https://github.com/asepsurahman03/joki-topup" class="btn" target="_blank">Code <i
                                    class="fas fa-code"></i></a>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Website Pendapatan & Pengeluaran Perbulan dan Pertahun -->
            <div class="project-card">
                <img draggable="false" src="./assets/images/projects/finance manager.png"
                    alt="Pendapatan & Pengeluaran Perbulan dan Pertahun" />
                <div class="content">
                    <div class="project-title">
                        <h3>Finance Manager</h3>
                    </div>
                    <div class="project-description">
                        <p>Sistem untuk mendata pendapatan & pengeluaran perbulan/pertahun Company</p>
                        <div class="project-buttons">
                            <a href="https://income.company.wuaze.com" class="btn" target="_blank"><i
                                    class="fas fa-eye"></i> View</a>
                            <a href="https://github.com/asepsurahman03/finance_manager" class="btn" target="_blank">Code
                                <i class="fas fa-code"></i></a>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Website Self Studio KMTech -->
            <div class="project-card">
                <img draggable="false" src="./assets/images/projects/studio foto.png"
                    alt="Self Studio KMTech Website" />
                <div class="content">
                    <div class="project-title">
                        <h3>Self Foto Studio KMTech</h3>
                    </div>
                    <div class="project-description">
                        <p>Website Studio Foto Self Studio KMTech dengan tampilan profesional.</p>
                        <div class="project-buttons">
                            <a href="https://self-studio-kmtech.kaldyta.com/" class="btn" target="_blank"><i
                                    class="fas fa-eye"></i> View</a>
                            <a href="https://github.com/asepsurahman03/studio_foto" class="btn" target="_blank">Code <i
                                    class="fas fa-code"></i></a>
                        </div>
                    </div>
                </div>
            </div>


        </div>

        <!-- Pagination Navigation -->
        <div class="pagination">
            <button class="btn" id="prevPage">« Prev</button>
            <div id="pageNumbers"></div>
            <button class="btn" id="nextPage">Next »</button>
        </div>

    </section>

    <script>
        // Data proyek (isi dengan proyek yang telah dibuat)
        const projects = [
            {
                img: "./assets/images/projects/codetech.png",
                title: "Website Codetech.id",
                desc: "Website resmi Codetech.id perusahaan digital berbasis teknologi yang menyediakan layanan pembuatan website, sistem informasi, dan edukasi. ",
                viewLink: "https://codetech-id.vercel.app",
                codeLink: "https://github.com/asepsurahman03/codetech"
            },

            {
                img: "./assets/images/projects/saveedu.png",
                title: "Saveedu",
                desc: "Saveedu adalah platform digital untuk memantau dan menganalisis data aktivitas belajar siswa SD untuk mendukung evaluasi pendidikan.",
                viewLink: "https://Saveedu-id.my.id",
                codeLink: "https://github.com/asepsurahman03/Saveedu"
            },

            {
                img: "./assets/images/projects/joki.png",
                title: "Website Codejoki.id",
                desc: "Website resmi Codejoki.id untuk layanan kebutuhan joki game Mobile Legends.",
                viewLink: "https://codejoki-id.vercel.app",
                codeLink: "https://github.com/asepsurahman03/codejoki"
            },

            {
                img: "./assets/images/projects/cuti.jpeg",
                title: "Website Cuti Karyawan",
                desc: "Website Cuti Karyawan untuk mengelola pengajuan, persetujuan, dan monitoring cuti karyawan dalam sebuah perusahaan.",
                viewLink: "#",
                codeLink: "#"
            },


            {
                img: "./assets/images/projects/finance manager.png",
                title: "Finance Manager",
                desc: "Sistem untuk mendata Pendapatan & pengeluaran perbulan/pertahun Company",
                viewLink: "https://income.company.wuaze.com",
                codeLink: "https://github.com/asepsurahman03/finance_manager"
            },



            {
                img: "./assets/images/projects/rumah makan.png",
                title: "E-Commerce Rumah Makan",
                desc: "Website e-commerce untuk rumah makan dengan fitur pemesanan makanan online.",
                viewLink: "https://template-kmtech-toko-online.vercel.app/",
                codeLink: "https://github.com/asepsurahman03/ecommerce-rumah-makan"
            },

            {
                img: "./assets/images/projects/bsi.png",
                title: "Website BSI",
                desc: "Website BSI  menyediakan berbagai layanan termasuk tabungan, pembiayaan, investasi, dan layanan digital lalu jam operasional.",
                viewLink: "#/",
                codeLink: "#"
            },

            {
                img: "./assets/images/projects/restoran.png",
                title: "E-Commerce Restorant",
                desc: "Website e-commerce Restoran rumah makan dengan fitur pemesanan makanan dan sistem kasir.",
                viewLink: "https://template-kmtech-toko-online.vercel.app/",
                codeLink: "https://github.com/asepsurahman03/ecommerce-rumah-makan"
            },

            {
                img: "./assets/images/projects/salon.png",
                title: "Website Beauty Salon",
                desc: "Website Beauty Salon memiliki fitur galeri, jadwal perawatan, dan sistem booking online.",
                viewLink: "#",
                codeLink: "#"
            },

            {
                img: "./assets/images/projects/coffe.png",
                title: "Website Coffe Tech",
                desc: "Website Coffe Tech Dilengkapi dengan fitur informasi produk, e-commerce untuk pemesanan kopi, serta sistem membership eksklusif dengan berbagai keuntungan spesial.",
                viewLink: "#",
                codeLink: "#"
            },

            {
                img: "./assets/images/projects/studio foto.png",
                title: "Self Foto Studio KMTech",
                desc: "Self Foto Studio KMTech adalah layanan self-photo studio modern yang dilengkapi dengan sistem booking online. Pelanggan dapat dengan mudah memilih jadwal, memesan sesi foto, dan berfoto tanpa harus antre.",
                viewLink: "https://self-studio-kmtech.kaldyta.com/",
                codeLink: "https://github.com/asepsurahman03/foto_studio"
            },


            {
                img: "./assets/images/projects/pugnator.png",
                title: "Website Pugnator",
                desc: "Website Pugnator Taekwondo berisikan informasi lengkap tentang event, kompetisi, dan jadwal latihan Taekwondo.",
                viewLink: "#",
                codeLink: "#"
            },

            {
                img: "./assets/images/projects/basket.png",
                title: "Website Bola Basket",
                desc: "Website informatif seputar bola basket yang membahas teknik dasar, aturan permainan dan strategi permainan.f",
                viewLink: "#",
                codeLink: "#"
            }
        ];

        // Variabel pagination
        const projectsPerPage = 6;
        let currentPage = 1;
        const totalPages = Math.ceil(projects.length / projectsPerPage);

        const projectsContainer = document.getElementById("projects-list");
        const prevPageBtn = document.getElementById("prevPage");
        const nextPageBtn = document.getElementById("nextPage");
        const pageNumbersContainer = document.getElementById("pageNumbers");

        // Fungsi untuk menampilkan proyek berdasarkan halaman
        function displayProjects() {
            projectsContainer.innerHTML = "";
            const startIndex = (currentPage - 1) * projectsPerPage;
            const endIndex = startIndex + projectsPerPage;
            const currentProjects = projects.slice(startIndex, endIndex);

            currentProjects.forEach((project) => {
                const projectCard = `
      <div class="project-card">
        <img draggable="false" src="${project.img}" alt="${project.title}" />
        <div class="content">
          <div class="project-title">
            <h3>${project.title}</h3>
          </div>
          <div class="project-description">
            <p>${project.desc}</p>
            <div class="project-buttons">
              <a href="${project.viewLink}" class="btn" target="_blank"><i class="fas fa-eye"></i> View</a>
              <a href="${project.codeLink}" class="btn" target="_blank">Code <i class="fas fa-code"></i></a>
            </div>
          </div>
        </div>
      </div>
    `;
                projectsContainer.innerHTML += projectCard;
            });

            updatePagination();
        }

        // Fungsi untuk memperbarui pagination
        function updatePagination() {
            pageNumbersContainer.innerHTML = "";

            for (let i = 1; i <= totalPages; i++) {
                const pageNumber = document.createElement("button");
                pageNumber.classList.add("page-number");
                if (i === currentPage) {
                    pageNumber.classList.add("active");
                }
                pageNumber.textContent = i;
                pageNumber.addEventListener("click", () => {
                    currentPage = i;
                    displayProjects();
                });
                pageNumbersContainer.appendChild(pageNumber);
            }

            prevPageBtn.disabled = currentPage === 1;
            nextPageBtn.disabled = currentPage === totalPages;
        }

        // Event listener untuk tombol pagination
        prevPageBtn.addEventListener("click", () => {
            if (currentPage > 1) {
                currentPage--;
                displayProjects();
            }
        });

        nextPageBtn.addEventListener("click", () => {
            if (currentPage < totalPages) {
                currentPage++;
                displayProjects();
            }
        });

        // Menampilkan proyek pertama kali
        displayProjects();



        // Fungsi untuk mengecek apakah elemen terlihat di viewport
        function isElementInViewport(el) {
            const rect = el.getBoundingClientRect();
            return (
                rect.top <= window.innerHeight * 0.5 && // 30% dari layar terlihat
                rect.bottom >= 0
            );
        }

        // Fungsi untuk menampilkan animasi jika elemen terlihat
        function handleScrollAnimation() {
            const projectSection = document.querySelector(".animate-project");

            if (isElementInViewport(projectSection)) {
                projectSection.classList.add("show"); // Tambahkan kelas 'show' untuk animasi
            } else {
                projectSection.classList.remove("show"); // Hapus kelas jika keluar dari viewport
            }
        }

        // Event listener untuk mendeteksi scroll
        window.addEventListener("scroll", handleScrollAnimation);

        // Jalankan sekali saat halaman pertama kali dimuat
        handleScrollAnimation();

    </script>
    <!-- Projects Section Ends -->
    <!-- work project section ends -->


    <!-- education section starts -->
    <section class="education" id="education">

        <h1 class="heading"><i class="fas fa-graduation-cap"></i> My <span>Education</span></h1>

        <p class="qoute">Education is not the learning of facts, but the training of the mind to think.</p>

        <div class="box-container">

            <!-- <div class="box">
        <div class="image">
        <img draggable="false" src="./assets/images/educat/college.jpg" alt="">
        </div>
        <div class="content">
        <h3>Nusa Putra University | S2 Magister Computer Science</h3>
        <p>IPK 3.50 | Data Science</p>
        <h4>2025 - Sekarang</h4>
        </div>
    </div> -->


            <div class="box">
                <div class="image">
                    <img draggable="false" src="./assets/images/educat/nusa putra.png" alt="">
                </div>
                <div class="content">
                    <a href="https://nusaputra.ac.id" target="_blank">
                        <h3>Nusa Putra University </h3>
                        <p>S1 Teknik Informatika | IPK 3.17</p>
                        <h4>2020-2024 | Completed</h4>
                </div>
            </div>
            </a>


            <div class="box">
                <div class="image">
                    <img draggable="false" src="./assets/images/educat/Sma pgri takokak.png" alt="">
                </div>
                <div class="content">
                    <a href="https://www.smapgritakokak.sch.id" target="_blank">
                        <h3>SMA PGRI Takokak </h3>
                        <p>Ilmu Pengetahuan Sosial</p>
                        <h4>2017 - 2020 | Complated</h4>
                </div>
            </div>
            </a>

        </div>
    </section>
    <!-- education section ends -->



    <!-- experience section starts -->
    <section class="experience" id="experience">

        <h2 class="heading"><i class="fas fa-briefcase"></i> Experience </h2>

        <div class="timeline">



            <div class="container right">
                <div class="content">
                    <div class="tag">
                        <h2>Codetech.id</h2>
                    </div>
                    <div class="desc">
                        <h3>Founder/CEO | Digital Marketing | Website Developer | Full Time</h3>
                        <p>Juni 2024 - Sekarang</p>
                    </div>
                </div>
            </div>

            <div class="container left">
                <div class="content">
                    <div class="tag">
                        <h2>PT. Kaldyta Mega Tech Nusa Putra University</h2>
                    </div>
                    <div class="desc">
                        <h3>Digital Marketing | Website Developer | Full Time</h3>
                        <p>Januari 2025 - Maret 2025</p>
                    </div>
                </div>
            </div>

            <div class="container right">
                <div class="content">
                    <div class="tag">
                        <h2>Nusa Putra University</h2>
                    </div>
                    <div class="desc">
                        <h3>Asisten Komputer Labolatorium, Network Engineering | Internship</h3>
                        <p>Agustus 2023 - Maret 2024</p>
                    </div>
                </div>
            </div>

            <div class="container left">
                <div class="content">
                    <div class="tag">
                        <h2>Diskominfo Kota Sukabumi</h2>
                    </div>
                    <div class="desc">
                        <h3>Web Development | Internship</h3>
                        <p>April 2023 - Juli 2023</p>
                    </div>
                </div>
            </div>
        </div>



        </div>

    </section>
    <!-- experience section ends -->


    <!-- Certifications Section Starts -->
    <section class="certifications-section" id="certifications">
        <h2 class="heading"><i class="fas fa-award"></i> Certifications & <span>Training</span></h2>

        <div class="certifications-container animate-certifications">
            <div class="cert-card">
                <h3>Artificial Intelligence</h3>
                <p>GTTC (Global Training & Test Center)</p>
                <span>04 Des 2023 - Sekarang</span>
            </div>

            <div class="cert-card">
                <h3>IT Specialist Python</h3>
                <p>GTTC (Global Training & Test Center)</p>
                <span>01 Des 2023 - Sekarang</span>
            </div>

            <div class="cert-card">
                <h3>MTCNA (MikroTik Certified Network Associate)</h3>
                <p>MikroTik</p>
                <span>15 Okt 2023 - 15 Okt 2025</span>
            </div>

            <div class="cert-card">
                <h3>Cloud Computing</h3>
                <p>GTTC (Global Training & Test Center)</p>
                <span>03 Des 2023 - Sekarang</span>
            </div>

            <div class="cert-card">
                <h3>British Council English Score</h3>
                <p>British Council</p>
                <span>31 Jan 2024 - Sekarang</span>
            </div>

            <div class="cert-card">
                <h3>Public Speaking</h3>
                <p>GTTC (Global Training & Test Center)</p>
                <span>05 Jul 2024 - Sekarang</span>
            </div>

            <div class="cert-card">
                <h3>TPA/TKDA</h3>
                <p>Koperasi Pegawai Bappenas</p>
                <span>Ags 2024 - Ags 2026</span>
            </div>

            <div class="cert-card">
                <h3>Certificate of Level</h3>
                <p>Altissia</p>
                <span>19 Jan 2024 - Sekarang</span>
            </div>
        </div>
    </section>
    <!-- Certifications Section Ends -->


    <script>
        // Fungsi untuk mengecek apakah elemen terlihat di viewport
        function isElementInViewport(el) {
            const rect = el.getBoundingClientRect();
            return (
                rect.top <= window.innerHeight * 0.75 && // 75% dari layar terlihat
                rect.bottom >= 0
            );
        }

        // Fungsi untuk menampilkan animasi jika elemen terlihat
        function handleScrollAnimation() {
            const certSection = document.querySelector(".animate-certifications");

            if (isElementInViewport(certSection)) {
                certSection.classList.add("show"); // Tambahkan kelas 'show' untuk animasi
            } else {
                certSection.classList.remove("show"); // Hapus kelas jika keluar dari viewport
            }
        }

        // Event listener untuk mendeteksi scroll
        window.addEventListener("scroll", handleScrollAnimation);

        // Jalankan sekali saat halaman pertama kali dimuat
        handleScrollAnimation();

    </script>

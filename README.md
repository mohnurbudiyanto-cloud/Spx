[index2.html](https://github.com/user-attachments/files/32968349/index2.html)
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lowongan Kurir SPX Jabar 2 — Area Cirebon</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', Roboto, sans-serif; }
        :root {
            --biru: #0b3d7c;
            --biru-terang: #1659b8;
            --emas: #f5b82e;
            --hijau: #00a86b;
            --putih: #ffffff;
            --abu-lembut: #f0f4f8;
        }
        body { background: linear-gradient(180deg, #e6eff9 0%, #c9daf0 100%); min-height: 100vh; padding-bottom: 40px; }
        .container { max-width: 900px; margin: 0 auto; padding: 20px; }

        /* Header */
        header { background: linear-gradient(135deg, var(--biru) 0%, var(--biru-terang) 100%); color: white; text-align: center; padding: 40px 25px; border-radius: 0 0 30px 30px; box-shadow: 0 8px 25px rgba(11,61,124,0.25); }
        .logo { font-size: 1.4rem; font-weight: 700; margin-bottom: 10px; }
        .logo span { color: var(--emas); }
        h1 { font-size: 2.2rem; margin: 15px 0; line-height: 1.2; }
        .sub-judul { font-size: 1.15rem; opacity: 0.9; margin-bottom: 25px; }
        .area { display: inline-block; background: rgba(255,255,255,0.2); padding: 10px 25px; border-radius: 50px; font-weight: 600; }

        /* Card */
        .card { background: white; border-radius: 20px; padding: 30px; margin-top: 25px; box-shadow: 0 6px 20px rgba(0,0,0,0.08); }
        .card h2 { color: var(--biru); font-size: 1.4rem; margin-bottom: 20px; display: flex; align-items: center; gap: 10px; border-bottom: 2px solid var(--emas); padding-bottom: 10px; }

        /* Peta */
        .map-container { width: 100%; height: 350px; border-radius: 15px; overflow: hidden; border: 3px solid var(--biru-terang); margin-bottom: 20px; }
        .map-container iframe { width: 100%; height: 100%; border: 0; }

        /* Daftar Lokasi */
        .lokasi-list { display: flex; flex-direction: column; gap: 15px; }
        .lokasi-card { background: var(--abu-lembut); padding: 18px; border-radius: 14px; border-left: 4px solid var(--biru-terang); transition: 0.2s; }
        .lokasi-card:hover { background: #dceafb; transform: translateX(5px); }
        .lokasi-nama { font-weight: 700; color: var(--biru); font-size: 1.05rem; margin-bottom: 6px; }
        .lokasi-alamat { font-size: 0.9rem; color: #444; margin-bottom: 10px; line-height: 1.6; }
        .btn-maps { display: inline-flex; align-items: center; gap: 6px; background: var(--biru-terang); color: white; padding: 8px 16px; border-radius: 50px; text-decoration: none; font-size: 0.85rem; font-weight: 600; transition: 0.2s; }
        .btn-maps:hover { background: var(--biru); }

        /* Benefit & Syarat */
        .grid-2 { display: grid; grid-template-columns: 1fr 1fr; gap: 20px; }
        @media (max-width: 650px) { .grid-2 { grid-template-columns: 1fr; } }
        .benefit-item { padding: 12px 15px; background: var(--abu-lembut); border-radius: 12px; margin-bottom: 10px; }
        .benefit-item strong { color: var(--biru); }
        .check::before { content: "✅ "; }
        .syarat { background: #fff9e8; border-left: 4px solid var(--emas); padding: 15px 20px; border-radius: 0 12px 12px 0; }

        /* Daftar */
        .daftar-box { background: linear-gradient(135deg, var(--hijau) 0%, #00c878 100%); color: white; text-align: center; padding: 35px 25px; border-radius: 20px; margin-top: 30px; box-shadow: 0 8px 25px rgba(0,168,107,0.25); }
        .btn-wa { display: inline-flex; align-items: center; gap: 10px; background: white; color: var(--hijau); font-weight: bold; padding: 15px 35px; border-radius: 50px; text-decoration: none; font-size: 1.1rem; margin: 15px 10px; transition: 0.3s; }
        .btn-wa:hover { transform: translateY(-3px); box-shadow: 0 8px 20px rgba(0,0,0,0.15); }
        .btn-link { display: inline-block; background: rgba(255,255,255,0.2); color: white; padding: 12px 25px; border-radius: 50px; text-decoration: none; font-weight: 600; margin-top: 10px; }
        .gratis { font-size: 1.1rem; font-weight: 700; margin-top: 20px; }
        .gratis span { color: #ffd700; font-size: 1.3rem; }

        footer { text-align: center; margin-top: 30px; color: #444; font-size: 0.9rem; }
    </style>
</head>
<body>

<div class="container">
    <!-- Header -->
    <header>
        <div class="logo">myrobin<span>.id</span> — A BetterPlace Company</div>
        <h1>LOWONGAN KERJA<br>KURIR SPX JABAR 2</h1>
        <p class="sub-judul">Bergabunglah Bersama Tim Pengantar Terpercaya</p>
        <div class="area">📍 Area: Kota & Kabupaten Cirebon</div>
    </header>

    <!-- Peta Utama -->
    <div class="card">
        <h2>🗺️ Peta Area Penempatan Cirebon</h2>
        <div class="map-container">
            <iframe 
                src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d126544.4314300963!2d108.51580165!3d-6.730436!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e6fb7f77f7f7f7f%3A0x4030bfbca0d51e0!2sCirebon%2C%20Jawa%20Barat!5e0!3m2!1sid!2sid!4v1727880000000!5m2!1sid!2sid" 
                allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade">
            </iframe>
        </div>

        <h2 style="margin-top:30px;">📍 Daftar Lokasi Hub & Alamat Lengkap</h2>
        
        <div class="lokasi-list" style="margin-top:20px;">

            <!-- 1 -->
            <div class="lokasi-card">
                <div class="lokasi-nama">Arjawinangun Hub</div>
                <div class="lokasi-alamat">
                    <strong>Alamat:</strong> Jl. Raya Arjawinangun, Kebonturi, Kec. Arjawinangun, Kab. Cirebon 45162<br>
                    <em>Patokan: Ruko Jejer Depan Kampus ITB Arjawinangun</em>
                </div>
                <a href="https://maps.app.goo.gl/UU8KVS7sVYEKifCLA" target="_blank" class="btn-maps">
                    📍 Buka di Google Maps
                </a>
            </div>

            <!-- 2 -->
            <div class="lokasi-card">
                <div class="lokasi-nama">Astanajapura Hub</div>
                <div class="lokasi-alamat">
                    <strong>Alamat:</strong> Jl. Kh. Wahid Hasyim No.97, Kanci, Kec. Astanajapura, Kab. Cirebon, Jawa Barat 45181
                </div>
                <a href="https://goo.gl/maps/9XdjBSnW4JrK56aZ6" target="_blank" class="btn-maps">
                    📍 Buka di Google Maps
                </a>
            </div>

            <!-- 3 -->
            <div class="lokasi-card">
                <div class="lokasi-nama">Ciledug Kulon Hub</div>
                <div class="lokasi-alamat">
                    <strong>Alamat:</strong> Samping Jempol Waterboom, Ciledug Kulon, Kab. Cirebon
                </div>
                <a href="https://maps.app.goo.gl/s936rorB26Gkw63FA" target="_blank" class="btn-maps">
                    📍 Buka di Google Maps
                </a>
            </div>

            <!-- 4 -->
            <div class="lokasi-card">
                <div class="lokasi-nama">Cirebon Hub</div>
                <div class="lokasi-alamat">
                    <strong>Alamat:</strong> Jl. Sunan Gunung Jati Blok IV, Kel. Klayan, Kec. Gunung Jati, Kab. Cirebon, Jawa Barat 45151
                </div>
                <a href="https://maps.app.goo.gl/yGT6LC9gSuGyTvUk6" target="_blank" class="btn-maps">
                    📍 Buka di Google Maps
                </a>
            </div>

            <!-- 5 -->
            <div class="lokasi-card">
                <div class="lokasi-nama">Depok Cirebon Hub</div>
                <div class="lokasi-alamat">
                    <strong>Alamat:</strong> Kasugengan Kidul, Kec. Depok, Kab. Cirebon, Jawa Barat
                </div>
                <a href="https://maps.app.goo.gl/Un8QEqoZFy5vrqo16" target="_blank" class="btn-maps">
                    📍 Buka di Google Maps
                </a>
            </div>

            <!-- 6 -->
            <div class="lokasi-card">
                <div class="lokasi-nama">Harjamukti Hub</div>
                <div class="lokasi-alamat">
                    <strong>Alamat:</strong> Jl. Jendral Ahmad Yani No.16, RT 001/RW 013, Kel. Pegambiran, Kec. Lemahwungkuk, Kota Cirebon, Jawa Barat
                </div>
                <a href="#" class="btn-maps" style="opacity:0.6; cursor:not-allowed;">
                    🔗 Belum tersedia link peta
                </a>
            </div>

            <!-- 7 -->
            <div class="lokasi-card">
                <div class="lokasi-nama">Kaliwedi Hub</div>
                <div class="lokasi-alamat">
                    <strong>Alamat:</strong> Karangsambung, Kec. Arjawinangun, Kab. Cirebon, Jawa Barat
                </div>
                <a href="https://maps.app.goo.gl/CZJvCH1JVrFaUo3dA" target="_blank" class="btn-maps">
                    📍 Buka di Google Maps
                </a>
            </div>

            <!-- 8 -->
            <div class="lokasi-card">
                <div class="lokasi-nama">Kedawung Hub</div>
                <div class="lokasi-alamat">
                    <strong>Alamat:</strong> Jl. Raya Pilangsari No.96, Kedawung, Kab. Cirebon<br>
                    <em>Patokan: Samping Kantor Pos Kedawung</em>
                </div>
                <a href="https://maps.app.goo.gl/754Yu1cCFiRZZa2F7" target="_blank" class="btn-maps">
                    📍 Buka di Google Maps
                </a>
            </div>

            <!-- 9 -->
            <div class="lokasi-card">
                <div class="lokasi-nama">Lemahabang Hub</div>
                <div class="lokasi-alamat">
                    <strong>Alamat:</strong> Jl. Sindanglaut-Ciawi Gajah, Asem, Kec. Lemahabang, Kab. Cirebon, Jawa Barat 45183
                </div>
                <a href="https://maps.app.goo.gl/7cnigQfdTzNEvXwL9" target="_blank" class="btn-maps">
                    📍 Buka di Google Maps
                </a>
            </div>

            <!-- 10 -->
            <div class="lokasi-card">
                <div class="lokasi-nama">Palimanan Hub</div>
                <div class="lokasi-alamat">
                    <strong>Alamat:</strong> Jl. KH. Agus Salim RT 019 RW 05, Desa Palimanan Barat, Kec. Gempol, Kab. Cirebon, Jawa Barat
                </div>
                <a href="#" class="btn-maps" style="opacity:0.6; cursor:not-allowed;">
                    🔗 Belum tersedia link peta
                </a>
            </div>

            <!-- 11 -->
            <div class="lokasi-card">
                <div class="lokasi-nama">Panguragan Hub</div>
                <div class="lokasi-alamat">
                    <strong>Alamat:</strong> Panguragan Wetan, Kec. Panguragan, Kab. Cirebon, Jawa Barat
                </div>
                <a href="https://maps.app.goo.gl/zFXYsLbz2Sb64gGb7" target="_blank" class="btn-maps">
                    📍 Buka di Google Maps
                </a>
            </div>

            <!-- 12 -->
            <div class="lokasi-card">
                <div class="lokasi-nama">Sumber Hub</div>
                <div class="lokasi-alamat">
                    <strong>Alamat:</strong> Jl. Ki Ageng Tapa, Kel. Gegunung, Kab. Cirebon, Jawa Barat
                </div>
                <a href="https://maps.app.goo.gl/SCCLsJtF9BwXb1Vr9" target="_blank" class="btn-maps">
                    📍 Buka di Google Maps
                </a>
            </div>

            <!-- 13 -->
            <div class="lokasi-card">
                <div class="lokasi-nama">Weru Hub</div>
                <div class="lokasi-alamat">
                    <strong>Alamat:</strong> Jl. Kisabalanang, Desa Megu Cilik, Kec. Weru, Kab. Cirebon, Jawa Barat 45154
                </div>
                <a href="https://maps.app.goo.gl/YZA1QgMCGhDtxyFS7" target="_blank" class="btn-maps">
                    📍 Buka di Google Maps
                </a>
            </div>

            <!-- 14 -->
            <div class="lokasi-card">
                <div class="lokasi-nama">Plumbon Hub</div>
                <div class="lokasi-alamat">
                    <strong>Alamat:</strong> Plumbon, Kab. Cirebon
                </div>
                <a href="https://maps.app.goo.gl/prsuECsWA49Va3uQ7" target="_blank" class="btn-maps">
                    📍 Buka di Google Maps
                </a>
            </div>

            <!-- 15 -->
            <div class="lokasi-card">
                <div class="lokasi-nama">Karangwareng Hub</div>
                <div class="lokasi-alamat">
                    <strong>Alamat:</strong> Kubangdeleg, Kec. Karangwareng, Kab. Cirebon, Jawa Barat
                </div>
                <a href="https://maps.app.goo.gl/B4NqdeL5chokC6Ma6" target="_blank" class="btn-maps">
                    📍 Buka di Google Maps
                </a>
            </div>

            <!-- 16 -->
            <div class="lokasi-card">
                <div class="lokasi-nama">Ciwaringin Hub</div>
                <div class="lokasi-alamat">
                    <strong>Alamat:</strong> Gintung Kidul, Kec. Ciwaringin, Kab. Cirebon, Jawa Barat
                </div>
                <a href="https://maps.app.goo.gl/FMotj7XvN8ABpESPA" target="_blank" class="btn-maps">
                    📍 Buka di Google Maps
                </a>
            </div>

            <!-- 17 -->
            <div class="lokasi-card">
                <div class="lokasi-nama">Susukan 2 Hub</div>
                <div class="lokasi-alamat">
                    <strong>Alamat:</strong> Gintung Lor, Kec. Susukan, Kab. Cirebon, Jawa Barat
                </div>
                <a href="https://maps.app.goo.gl/jr4HthefXqbfGgGeA" target="_blank" class="btn-maps">
                    📍 Buka di Google Maps
                </a>
            </div>

        </div>
    </div>

    <!-- Benefit -->
    <div class="grid-2">
        <div class="card">
            <h2>💼 Benefit Mitra</h2>
            <div class="benefit-item check"><strong>SIM C (Motor):</strong> Rp1.600 – Rp1.900 / paket</div>
            <div class="benefit-item check"><strong>SIM A (Mobil):</strong> Rp4.750 – Rp5.500 / paket</div>
            <div class="benefit-item check">Gaji dibayar tiap 2 minggu</div>
        </div>
        <div class="card">
            <h2>🚗 Benefit Plus</h2>
            <div class="benefit-item check"><strong>Gaji Pokok:</strong> 80% UMK Setempat (Tgl 25)</div>
            <div class="benefit-item check"><strong>Bonus Produktivitas:</strong> Dibayar tgl 15</div>
            <div class="benefit-item check">Tunjangan JKK & JKM</div>
        </div>
    </div>

    <!-- Syarat -->
    <div class="card">
        <h2>📋 Syarat Pendaftaran</h2>
        <div class="syarat">
            <p>✅ KTP</p>
            <p>✅ SIM C / SIM A (sesuai kendaraan)</p>
            <p>✅ STNK Kendaraan</p>
            <p>✅ Kendaraan Pribadi</p>
        </div>
    </div>

    <!-- Daftar -->
    <div class="daftar-box">
        <h2 style="color:white; border:none; font-size:1.6rem; margin:0 0 10px 0;">📩 DAFTAR SEKARANG</h2>
        <p>Hubungi Recruiter Langsung via WhatsApp</p>
        
        <a href="https://wa.me/6283166142120" target="_blank" class="btn-wa">
            💬 WhatsApp: 0831-6614-2120 (Budi)
        </a>
        
        <br>
        <a href="https://bit.ly/KurirMYRJabar" target="_blank" class="btn-link">
            🔗 Atau Daftar Lewat Link: bit.ly/KurirMYRJabar
        </a>
        
        <p class="gratis"><span>⭐</span> PENDAFTARAN GRATIS! TIDAK DIPUNGUT BIAYA APAPUN <span>⭐</span></p>
    </div>

    <footer>
        <p>&copy; 2026 myrobin.id — Lowongan Kerja Kurir SPX Jabar 2</p>
        <p>Semoga berhasil! 🤝</p>
    </footer>
</div>

</body>
</html>

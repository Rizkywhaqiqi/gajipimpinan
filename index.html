<html lang="en" class="scroll-smooth">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Dashboard Admin Keuangan</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"
  />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&display=swap" rel="stylesheet" />
  <style>
    body {
      font-family: 'Inter', sans-serif;
    }
    tbody::-webkit-scrollbar {
      height: 8px;
    }
    tbody::-webkit-scrollbar-thumb {
      background-color: #a0aec0;
      border-radius: 4px;
    }
  </style>
</head>
<body class="bg-gray-50 text-gray-800 min-h-screen flex flex-col">
  <div class="max-w-5xl mx-auto w-full flex flex-col bg-white shadow-lg rounded-lg border border-gray-200 overflow-hidden my-8">
    <!-- Header -->
    <header class="flex justify-between items-center bg-white border-b border-gray-200 px-6 py-4">
      <div class="flex items-center space-x-3">
        <div class="w-10 h-10 bg-indigo-600 rounded flex items-center justify-center text-white font-bold text-lg select-none">L</div>
        <h1 class="text-xl font-semibold tracking-wide">Dashboard Admin Keuangan</h1>
      </div>
      <button class="text-indigo-600 font-semibold hover:text-indigo-800 transition">Logout</button>
    </header>

    <!-- Controls -->
    <section class="flex flex-col sm:flex-row justify-between items-center gap-4 px-6 py-4 border-b border-gray-200">
      <div class="flex items-center space-x-3 w-full sm:w-auto">
        <label for="jenisSelect" class="font-medium text-gray-700 whitespace-nowrap">Pilih Jenis:</label>
        <select id="jenisSelect" class="border border-gray-300 rounded-md bg-white text-gray-900 text-sm font-mono px-3 py-1.5 focus:outline-none focus:ring-2 focus:ring-indigo-500 focus:border-indigo-500 transition w-40">
          <option value="gaji">Gaji</option>
          <option value="tpp">TPP V</option>
        </select>
      </div>
      <div class="text-gray-600 font-medium text-sm whitespace-nowrap flex items-center space-x-2">
        <label for="periodeInput" class="font-mono">Periode:</label>
        <input
          type="month"
          id="periodeInput"
          class="border border-gray-300 rounded-md bg-white text-gray-900 text-sm font-mono px-3 py-1.5 focus:outline-none focus:ring-2 focus:ring-indigo-500 focus:border-indigo-500 transition"
          value="2025-09"
          aria-label="Periode"
        />
      </div>
    </section>

    <!-- Ringkasan Progress -->
    <section class="px-6 py-4 border-b border-gray-200 flex flex-col sm:flex-row justify-between gap-4 text-sm font-mono">
      <div>
        <h2 class="text-gray-900 font-semibold mb-2">Ringkasan Progress</h2>
        <ul class="list-disc list-inside space-y-1 text-gray-700">
          <li>Gaji September 2025</li>
          <li>TPP Juli 2025</li>
        </ul>
      </div>
      <div class="text-right text-gray-600 space-y-1 min-w-[100px]">
        <div>5/15 selesai</div>
        <div>17/17 selesai</div>
      </div>
    </section>

    <!-- Dynamic Tahapan Description -->
    <section id="tahapanDescription" class="px-6 py-4 border-b border-gray-200 text-xs text-gray-700 whitespace-pre-line font-mono leading-relaxed max-h-48 overflow-y-auto"></section>

    <!-- Detail Tahapan -->
    <section class="px-6 py-4 border-b border-gray-200 text-xs font-mono">
      <h3 id="detailTitle" class="font-semibold mb-2">Detail Tahapan GAJI - September 2025</h3>
      <div class="overflow-x-auto">
        <table class="min-w-full border border-black border-collapse text-xs">
          <thead>
            <tr class="border border-black bg-gray-100">
              <th class="border border-black px-1 text-center w-8">No</th>
              <th class="border border-black px-1 text-left">Tahapan</th>
              <th class="border border-black px-1 text-center w-16">Status</th>
              <th class="border border-black px-1 text-center w-20">Update</th>
            </tr>
          </thead>
          <tbody id="tahapanTableBody" class="bg-white"></tbody>
        </table>
      </div>
    </section>

    <!-- + Update Tahapan -->
    <button
      class="w-full text-indigo-600 font-semibold text-left px-6 py-2 hover:bg-indigo-50 transition flex items-center space-x-2 border-b border-gray-200 font-mono"
      id="toggleUpdateForm"
      aria-expanded="false"
      aria-controls="updateForm"
    >
      <i class="fas fa-plus"></i>
      <span>+ Update Tahapan</span>
    </button>

    <!-- Update Tahapan form -->
    <section id="updateForm" class="px-6 py-4 text-xs text-gray-700 font-mono hidden">
      <div class="mb-2 font-semibold">Update Tahapan</div>
      <form onsubmit="return false;" class="space-y-2">
        <div>
          <label for="inputTahapan" class="block mb-0.5">Tahapan :</label>
          <input
            type="text"
            id="inputTahapan"
            readonly
            value="Pembuatan SPP & SPM Gaji"
            class="w-full border border-black px-1 py-0.5 bg-gray-100"
          />
        </div>
        <div>
          <label for="inputStatus" class="block mb-0.5">Status :</label>
          <input
            type="text"
            id="inputStatus"
            readonly
            value="[ Pending | Proses | Selesai ]"
            class="w-full border border-black px-1 py-0.5 bg-gray-100"
          />
        </div>
        <div>
          <label for="inputTanggal" class="block mb-0.5">Tanggal :</label>
          <input
            type="text"
            id="inputTanggal"
            readonly
            value="30/08/2025"
            class="w-full border border-black px-1 py-0.5 bg-gray-100"
          />
        </div>
        <div>
          <label for="inputCatatan" class="block mb-0.5">Catatan :</label>
          <textarea
            id="inputCatatan"
            readonly
            rows="2"
            class="w-full border border-black px-1 py-0.5 bg-gray-100 resize-none"
          >[Input di aplikasi SIMDA ]</textarea>
        </div>
        <div>
          <label for="inputDokumen" class="block mb-0.5">Dokumen :</label>
          <input
            type="text"
            id="inputDokumen"
            readonly
            value="[ Link GDrive ]"
            class="w-full border border-black px-1 py-0.5 bg-gray-100"
          />
        </div>
        <div class="flex space-x-2">
          <button
            type="button"
            class="border border-black px-3 py-1 font-semibold hover:bg-gray-200 transition"
          >
            Simpan Draft
          </button>
          <button
            type="button"
            class="border border-black px-3 py-1 font-semibold hover:bg-gray-200 transition"
          >
            Kirim ke Pimpinan
          </button>
        </div>
      </form>
    </section>
  </div>

  <script>
    const gajiDescription = `Penerbitan daftar gaji – BKD
Pendistribusian daftar gaji ke UPT & RSUD – Subbag Keuangan dan Perlengkapan
Verifikasi daftar transfer rekening gaji – UPT & RSUD
Kompilasi daftar transfer rekening gaji – Subbag Keuangan dan Perlengkapan
Pembuatan template gaji pada aplikasi – Subbag Keuangan dan Perlengkapan
Pembuatan SPP & SPM gaji – Subbag Keuangan dan Perlengkapan
Pembuatan billing pajak (PPH, IWP, JHT, JKK, JKM) – Subbag Keuangan dan Perlengkapan
Verifikasi SPP & SPM gaji – Subbag Keuangan dan Perlengkapan
Pengesahan SPP & SPM gaji – Pejabat berwenang Dinkes & KB
Penyampaian SPP & SPM gaji ke BKD – Subbag Keuangan dan Perlengkapan
Verifikasi SPP & SPM gaji – BKD
Pengesahan SP2D gaji – Pejabat berwenang BKD
Penyampaian SP2D gaji ke Kasda – BKD
Pencairan SP2D ke rekening bendahara pengeluaran Dinkes & KB – Bank Kalbar
Transfer ke rekening Pegawai – Bank Kalbar`;

    const tppDescription = `Tahapan Lengkap – Status TPP
Periode: Juli 2025
Estimasi: TPP sudah ditransfer per 27 Agustus 2025

Laporan daftar absensi (softfile & hardfile) – UPT & RSUD
Verifikasi laporan daftar absensi – Subbag Umum Aparatur
Penyampaian laporan daftar absensi ke BKD – Subbag Keuangan & Perlengkapan
Penerbitan daftar TPP – BKD
Kompilasi daftar transfer rekening TPP – Subbag Keuangan & Perlengkapan
Pembuatan template TPP pada aplikasi – Subbag Keuangan & Perlengkapan
Pembuatan SPP & SPM TPP – Subbag Keuangan & Perlengkapan
Pembuatan billing pajak, IWP – Subbag Keuangan & Perlengkapan
Verifikasi SPP & SPM TPP – Subbag Keuangan & Perlengkapan
Pengesahan SPP & SPM TPP – Pejabat berwenang Dinkes & KB
Penyampaian SPP & SPM TPP ke BKD – Subbag Keuangan & Perlengkapan
Verifikasi SPP & SPM TPP – BKD
Penerbitan SP2D TPP – BKD
Pengesahan SP2D TPP – Pejabat berwenang BKD
Penyampaian SP2D TPP ke Kasda – BKD
Pencairan SP2D ke rekening bendahara pengeluaran Dinkes & KB – Bank Kalbar
Transfer ke rekening Pegawai – Bank Kalbar`;

    const gajiRows = [
      { no: 1, tahapan: "Penerbitan daftar gaji – BKD", status: "Done", update: "27/08" },
      { no: 2, tahapan: "Pendistribusian daftar gaji ke UPT & RSUD – Subbag Keuangan dan Perlengkapan", status: "Done", update: "27/08" },
      { no: 3, tahapan: "Verifikasi daftar transfer rekening gaji – UPT & RSUD", status: "Done", update: "27/08" },
      { no: 4, tahapan: "Kompilasi daftar transfer rekening gaji – Subbag Keuangan dan Perlengkapan", status: "Done", update: "27/08" },
      { no: 5, tahapan: "Pembuatan template gaji pada aplikasi – Subbag Keuangan dan Perlengkapan", status: "Done", update: "28/08" },
      { no: 6, tahapan: "Pembuatan SPP & SPM gaji – Subbag Keuangan dan Perlengkapan", status: "Proses", update: "30/08" },
      { no: 7, tahapan: "Pembuatan billing pajak (PPH, IWP, JHT, JKK, JKM) – Subbag Keuangan dan Perlengkapan", status: "Pending", update: "-" },
      { no: 8, tahapan: "Verifikasi SPP & SPM gaji – Subbag Keuangan dan Perlengkapan", status: "Pending", update: "-" },
      { no: 9, tahapan: "Pengesahan SPP & SPM gaji – Pejabat berwenang Dinkes & KB", status: "Pending", update: "-" },
      { no: 10, tahapan: "Penyampaian SPP & SPM gaji ke BKD – Subbag Keuangan dan Perlengkapan", status: "Pending", update: "-" },
      { no: 11, tahapan: "Verifikasi SPP & SPM gaji – BKD", status: "Pending", update: "-" },
      { no: 12, tahapan: "Pengesahan SP2D gaji – Pejabat berwenang BKD", status: "Pending", update: "-" },
      { no: 13, tahapan: "Penyampaian SP2D gaji ke Kasda – BKD", status: "Pending", update: "-" },
      { no: 14, tahapan: "Pencairan SP2D ke rekening bendahara pengeluaran Dinkes & KB – Bank Kalbar", status: "Pending", update: "-" },
      { no: 15, tahapan: "Transfer ke rekening Pegawai – Bank Kalbar", status: "Pending", update: "-" },
    ];

    const tppRows = [
      { no: 1, tahapan: "Laporan daftar absensi (softfile & hardfile) – UPT & RSUD", status: "Done", update: "27/08" },
      { no: 2, tahapan: "Verifikasi laporan daftar absensi – Subbag Umum Aparatur", status: "Done", update: "27/08" },
      { no: 3, tahapan: "Penyampaian laporan daftar absensi ke BKD – Subbag Keuangan & Perlengkapan", status: "Done", update: "27/08" },
      { no: 4, tahapan: "Penerbitan daftar TPP – BKD", status: "Done", update: "27/08" },
      { no: 5, tahapan: "Kompilasi daftar transfer rekening TPP – Subbag Keuangan & Perlengkapan", status: "Done", update: "27/08" },
      { no: 6, tahapan: "Pembuatan template TPP pada aplikasi – Subbag Keuangan & Perlengkapan", status: "Done", update: "28/08" },
      { no: 7, tahapan: "Pembuatan SPP & SPM TPP – Subbag Keuangan & Perlengkapan", status: "Proses", update: "30/08" },
      { no: 8, tahapan: "Pembuatan billing pajak, IWP – Subbag Keuangan & Perlengkapan", status: "Pending", update: "-" },
      { no: 9, tahapan: "Verifikasi SPP & SPM TPP – Subbag Keuangan & Perlengkapan", status: "Pending", update: "-" },
      { no: 10, tahapan: "Pengesahan SPP & SPM TPP – Pejabat berwenang Dinkes & KB", status: "Pending", update: "-" },
      { no: 11, tahapan: "Penyampaian SPP & SPM TPP ke BKD – Subbag Keuangan & Perlengkapan", status: "Pending", update: "-" },
      { no: 12, tahapan: "Verifikasi SPP & SPM TPP – BKD", status: "Pending", update: "-" },
      { no: 13, tahapan: "Penerbitan SP2D TPP – BKD", status: "Pending", update: "-" },
      { no: 14, tahapan: "Pengesahan SP2D TPP – Pejabat berwenang BKD", status: "Pending", update: "-" },
      { no: 15, tahapan: "Penyampaian SP2D TPP ke Kasda – BKD", status: "Pending", update: "-" },
      { no: 16, tahapan: "Pencairan SP2D ke rekening bendahara pengeluaran Dinkes & KB – Bank Kalbar", status: "Pending", update: "-" },
      { no: 17, tahapan: "Transfer ke rekening Pegawai – Bank Kalbar", status: "Pending", update: "-" },
    ];

    function createStatusCell(status) {
      let color = "text-gray-500";
      let icon = "fa-hourglass-half";
      if (status === "Done") {
        color = "text-green-600";
        icon = "fa-check-circle";
      } else if (status === "Proses") {
        color = "text-yellow-500";
        icon = "fa-spinner fa-spin";
      } else if (status === "Pending") {
        color = "text-gray-400";
        icon = "fa-clock";
      }
      return `<td class="border border-black px-1 text-center ${color} font-semibold flex justify-center items-center space-x-1">
                <i class="fas ${icon}"></i><span>${status}</span>
              </td>`;
    }

    function renderTable(rows) {
      const tbody = document.getElementById("tahapanTableBody");
      tbody.innerHTML = "";
      rows.forEach(({ no, tahapan, status, update }) => {
        const tr = document.createElement("tr");
        tr.className = "";
        tr.innerHTML = `
          <td class="border border-black px-1 text-center">${no}</td>
          <td class="border border-black px-1">${tahapan}</td>
          ${createStatusCell(status)}
          <td class="border border-black px-1 text-center">${update}</td>
        `;
        tbody.appendChild(tr);
      });
    }

    function formatPeriode(dateStr) {
      if (!dateStr) return "[ Sept 2025 ]";
      const [year, month] = dateStr.split("-");
      if (!year || !month) return "[ Sept 2025 ]";
      const monthNames = ["Jan", "Feb", "Mar", "Apr", "Mei", "Jun", "Jul", "Ags", "Sept", "Okt", "Nov", "Des"];
      const mIndex = parseInt(month, 10) - 1;
      const monthName = monthNames[mIndex] || "Sept";
      return `[ ${monthName} ${year} ]`;
    }

    function updateContent() {
      const select = document.getElementById("jenisSelect");
      const periodeInput = document.getElementById("periodeInput");
      const jenis = select.value;
      const periode = periodeInput.value;
      const desc = document.getElementById("tahapanDescription");
      const title = document.getElementById("detailTitle");
      const inputTahapan = document.getElementById("inputTahapan");
      const periodeFormatted = formatPeriode(periode);

      // Update periode text
      document.querySelector('section.flex.flex-col.sm\\:flex-row > div.text-gray-600.font-medium.text-sm').innerHTML =
        `Periode: <span class="font-semibold">${periodeFormatted}</span>`;

      if (jenis === "gaji") {
        desc.textContent = gajiDescription;
        title.textContent = `Detail Tahapan GAJI - ${periodeFormatted.replace(/[\[\]]/g, '')}`;
        renderTable(gajiRows);
        inputTahapan.value = "Pembuatan SPP & SPM Gaji";
      } else {
        desc.textContent = tppDescription;
        title.textContent = `Detail Tahapan TPP - ${periodeFormatted.replace(/[\[\]]/g, '')}`;
        renderTable(tppRows);
        inputTahapan.value = "Pembuatan SPP & SPM TPP";
      }
    }

    document.getElementById("jenisSelect").addEventListener("change", updateContent);
    document.getElementById("periodeInput").addEventListener("change", updateContent);

    // Toggle update form visibility
    const toggleBtn = document.getElementById("toggleUpdateForm");
    const updateForm = document.getElementById("updateForm");
    toggleBtn.addEventListener("click", () => {
      const isHidden = updateForm.classList.toggle("hidden");
      toggleBtn.setAttribute("aria-expanded", !isHidden);
    });

    // Initial load
    updateContent();
  </script>
</body>
</html>

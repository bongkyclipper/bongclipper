<%- include('partials/header') %>

  <div class="grain"></div>

  <header class="topbar">
    <div class="brand">
      <span class="brand-mark">[&nbsp;⏱&nbsp;]</span>
      <span class="brand-name">Clipreel</span>
    </div>
    <div class="topbar-actions">
      <span class="tag">yt-dlp + ffmpeg</span>
      <button id="themeToggle" class="icon-btn" title="Ubah tema" aria-label="Ubah tema">◐</button>
    </div>
  </header>

  <main class="wrap">

    <!-- ===== HERO / URL INPUT ===== -->
    <section class="hero">
      <p class="eyebrow">TIMECODE 00:00:00 — 00:00:00</p>
      <h1>Potong momen terbaik dari video YouTube mana pun.</h1>
      <p class="lede">Tempel tautan, tandai in-point dan out-point, lalu ekspor. Tidak perlu mengunduh seluruh video.</p>

      <form id="urlForm" class="url-form" autocomplete="off">
        <div id="dropzone" class="dropzone">
          <input
            type="text"
            id="urlInput"
            name="url"
            placeholder="https://youtube.com/watch?v=…  atau tempel/drop link di sini"
            required
          />
          <button type="submit" id="loadBtn" class="btn btn-primary">
            <span class="btn-label">Muat Video</span>
          </button>
        </div>
      </form>
      <p id="urlError" class="field-error" hidden></p>
    </section>

    <!-- ===== PREVIEW + TRIM PANEL ===== -->
    <section id="previewSection" class="panel preview-panel" hidden>
      <div class="preview-grid">
        <div class="thumb-wrap">
          <img id="thumbImg" src="" alt="Thumbnail video" />
          <span id="durationBadge" class="duration-badge">00:00:00</span>
        </div>

        <div class="meta">
          <h2 id="videoTitle">—</h2>
          <p id="videoChannel" class="muted">—</p>

          <dl class="meta-grid">
            <div><dt>Durasi</dt><dd id="metaDuration">—</dd></div>
            <div><dt>Estimasi Ukuran</dt><dd id="metaSize">—</dd></div>
            <div><dt>Subtitle</dt><dd id="metaSubtitle">—</dd></div>
            <div><dt>Resolusi Tersedia</dt><dd id="metaResolutions">—</dd></div>
          </dl>
        </div>
      </div>

      <!-- Signature element: timecode ruler menampilkan rentang clip terpilih -->
      <div class="ruler-block">
        <div class="ruler" id="ruler">
          <div class="ruler-ticks" id="rulerTicks"></div>
          <div class="ruler-selection" id="rulerSelection"></div>
        </div>
      </div>

      <form id="clipForm" class="clip-form">
        <div class="field-row">
          <label>
            <span class="field-label">IN — start</span>
            <input type="text" id="startInput" name="start" placeholder="00:00:00" value="00:00:00" required />
          </label>
          <label>
            <span class="field-label">OUT — end</span>
            <input type="text" id="endInput" name="end" placeholder="00:01:00" required />
          </label>
          <label>
            <span class="field-label">Resolusi</span>
            <select id="resolutionSelect" name="resolution">
              <option value="original">Original</option>
              <option value="1080p">1080p</option>
              <option value="720p" selected>720p</option>
              <option value="480p">480p</option>
              <option value="360p">360p</option>
            </select>
          </label>
        </div>
        <p id="clipError" class="field-error" hidden></p>
        <button type="submit" id="clipBtn" class="btn btn-accent">
          <span class="btn-label">Potong &amp; Ekspor Clip</span>
        </button>
      </form>
    </section>

    <!-- ===== PROGRESS PANEL ===== -->
    <section id="progressSection" class="panel progress-panel" hidden>
      <div class="progress-head">
        <span id="progressStage" class="progress-stage">Menunggu antrian…</span>
        <span id="progressPercent" class="progress-percent">0%</span>
      </div>
      <div class="progress-track">
        <div id="progressBar" class="progress-bar"></div>
      </div>
      <div class="vu-meter" id="vuMeter" aria-hidden="true"></div>
    </section>

    <!-- ===== RESULT PANEL ===== -->
    <section id="resultSection" class="panel result-panel" hidden>
      <div class="result-icon">✓</div>
      <div>
        <h3>Clip siap diunduh</h3>
        <p id="resultFilename" class="muted mono">—</p>
      </div>
      <div class="result-actions">
        <a id="downloadBtn" class="btn btn-primary" href="#" download>Download</a>
        <button id="deleteBtn" class="btn btn-ghost">Hapus File</button>
      </div>
    </section>

  </main>

  <footer class="page-footer">
    <p>Clipreel — dibuat untuk memotong video secara efisien. File otomatis dihapus setelah 30 menit.</p>
  </footer>

  <div id="toastContainer" class="toast-container" aria-live="polite"></div>

<%- include('partials/footer') %>

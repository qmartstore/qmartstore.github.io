<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Q-Mart Product Manager</title>
<link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&family=DM+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
:root {
  --teal: #0d9488;
  --teal-dark: #0f766e;
  --teal-light: #ccfbf1;
  --teal-xlight: #f0fdfa;
  --dark: #0f172a;
  --mid: #475569;
  --muted: #94a3b8;
  --border: #e2e8f0;
  --bg: #f8fafc;
  --white: #ffffff;
}
* { margin: 0; padding: 0; box-sizing: border-box; }
body { font-family: 'DM Sans', sans-serif; background: var(--bg); color: var(--dark); min-height: 100vh; }

.header {
  background: var(--dark);
  padding: 18px 24px;
  display: flex; align-items: center; gap: 12px;
}
.header-logo {
  width: 36px; height: 36px; border-radius: 8px;
  background: var(--teal);
  display: flex; align-items: center; justify-content: center;
  font-weight: 800; font-size: 16px; color: white;
}
.header-title { color: white; font-size: 16px; font-weight: 700; }
.header-sub { color: var(--muted); font-size: 12px; margin-top: 1px; }

.container { max-width: 860px; margin: 0 auto; padding: 32px 16px; }

.section-title {
  font-size: 11px; font-weight: 700; color: var(--muted);
  text-transform: uppercase; letter-spacing: 1px;
  margin-bottom: 12px; margin-top: 32px;
  display: flex; align-items: center; gap: 8px;
}
.section-title:first-child { margin-top: 0; }
.section-title::after { content: ''; flex: 1; height: 1px; background: var(--border); }

.card {
  background: var(--white);
  border: 1px solid var(--border);
  border-radius: 16px;
  padding: 24px;
  margin-bottom: 16px;
  box-shadow: 0 2px 12px rgba(0,0,0,0.05);
}

label {
  display: block;
  font-size: 12px; font-weight: 600; color: var(--mid);
  text-transform: uppercase; letter-spacing: 0.5px;
  margin-bottom: 8px;
}

input[type="text"], input[type="number"], textarea, select {
  width: 100%; padding: 12px 14px;
  border: 1.5px solid var(--border); border-radius: 10px;
  font-family: 'DM Sans', sans-serif; font-size: 14px;
  color: var(--dark); outline: none;
  transition: border-color 0.2s;
  background: var(--bg);
}
input:focus, textarea:focus, select:focus { border-color: var(--teal); background: white; }
textarea { line-height: 1.6; resize: vertical; }

.row2 { display: grid; grid-template-columns: 1fr 1fr; gap: 16px; }
@media(max-width:500px){ .row2 { grid-template-columns: 1fr; } }

.btn {
  background: var(--teal); color: white; border: none;
  border-radius: 10px; padding: 13px 24px;
  font-family: 'DM Sans', sans-serif; font-size: 15px; font-weight: 700;
  cursor: pointer; transition: background 0.2s;
  display: inline-flex; align-items: center; gap: 8px;
}
.btn:hover { background: var(--teal-dark); }
.btn:disabled { background: var(--muted); cursor: not-allowed; }
.btn-ghost {
  background: none; border: 1.5px solid var(--border); color: var(--mid);
}
.btn-ghost:hover { background: var(--bg); }

.btn-row { display: flex; gap: 10px; flex-wrap: wrap; margin-top: 16px; }

.result-box {
  background: var(--teal-xlight);
  border: 1.5px solid var(--teal-light);
  border-radius: 10px; padding: 16px;
  margin-top: 16px; display: none;
}
.result-label {
  font-size: 11px; font-weight: 700; color: var(--teal-dark);
  text-transform: uppercase; letter-spacing: 0.5px; margin-bottom: 8px;
}
.result-text {
  font-family: 'DM Mono', monospace;
  font-size: 13px; color: var(--dark);
  line-height: 1.6; word-break: break-word;
  white-space: pre-wrap;
}
.copy-btn {
  margin-top: 10px; background: var(--teal); color: white;
  border: none; border-radius: 8px; padding: 8px 16px;
  font-family: 'DM Sans', sans-serif; font-size: 13px; font-weight: 600;
  cursor: pointer; transition: background 0.2s;
}
.copy-btn:hover { background: var(--teal-dark); }

.loading {
  display: none; align-items: center; gap: 10px;
  margin-top: 16px; color: var(--mid); font-size: 14px;
}
.spinner {
  width: 18px; height: 18px; border: 2px solid var(--border);
  border-top-color: var(--teal); border-radius: 50%;
  animation: spin 0.8s linear infinite; flex-shrink: 0;
}
@keyframes spin { to { transform: rotate(360deg); } }

.error-box {
  background: #fef2f2; border: 1.5px solid #fecaca;
  border-radius: 10px; padding: 14px;
  margin-top: 14px; display: none;
  color: #dc2626; font-size: 14px;
}

.tip {
  background: var(--bg); border: 1px solid var(--border);
  border-radius: 10px; padding: 14px 16px;
  font-size: 13px; color: var(--mid); line-height: 1.6;
}
.tip strong { color: var(--dark); }
.pipe { color: var(--teal); font-weight: 700; font-family: monospace; }

/* Image uploader */
.upload-zone {
  border: 2px dashed var(--border); border-radius: 12px;
  padding: 32px 20px; text-align: center; cursor: pointer;
  transition: border-color 0.2s, background 0.2s;
  background: var(--bg);
}
.upload-zone:hover, .upload-zone.dragover { border-color: var(--teal); background: var(--teal-xlight); }
.upload-zone svg { color: var(--muted); margin-bottom: 10px; }
.upload-zone p { font-size: 14px; color: var(--mid); }
.upload-zone span { font-size: 12px; color: var(--muted); display: block; margin-top: 4px; }

.preview-grid {
  display: grid; grid-template-columns: repeat(auto-fill, minmax(90px, 1fr));
  gap: 10px; margin-top: 16px;
}
.preview-item {
  position: relative; border-radius: 10px; overflow: hidden;
  border: 1.5px solid var(--border); aspect-ratio: 1;
  background: var(--bg);
}
.preview-item img { width: 100%; height: 100%; object-fit: cover; display: block; }
.preview-item .remove-btn {
  position: absolute; top: 4px; right: 4px;
  width: 22px; height: 22px; border-radius: 50%;
  background: rgba(15,23,42,0.7); color: white; border: none;
  font-size: 13px; cursor: pointer; display: flex;
  align-items: center; justify-content: center; line-height: 1;
}
.preview-item .img-status {
  position: absolute; bottom: 0; left: 0; right: 0;
  font-size: 10px; font-weight: 600; text-align: center;
  padding: 3px; background: rgba(15,23,42,0.6); color: white;
}
.preview-item .img-status.done { background: rgba(13,148,136,0.85); }
.preview-item .img-status.err { background: rgba(220,38,38,0.85); }

/* Auth bar */
.auth-bar {
  display: flex; align-items: center; gap: 12px;
  padding: 12px 16px; border-radius: 10px;
  background: var(--bg); border: 1px solid var(--border);
  margin-bottom: 16px;
}
.auth-dot { width: 10px; height: 10px; border-radius: 50%; background: var(--muted); flex-shrink: 0; }
.auth-dot.connected { background: #22c55e; }
.auth-text { font-size: 13px; color: var(--mid); flex: 1; }
.auth-btn {
  background: var(--teal); color: white; border: none;
  border-radius: 8px; padding: 7px 14px;
  font-family: 'DM Sans', sans-serif; font-size: 13px; font-weight: 600;
  cursor: pointer;
}
.auth-btn:hover { background: var(--teal-dark); }

/* Final row */
.final-row-box {
  background: var(--dark); border-radius: 12px; padding: 18px;
  margin-top: 20px; display: none;
}
.final-row-label { font-size: 11px; font-weight: 700; color: var(--muted); text-transform: uppercase; letter-spacing: 0.5px; margin-bottom: 10px; }
.final-row-text {
  font-family: 'DM Mono', monospace; font-size: 12px;
  color: #a3e635; word-break: break-all; line-height: 1.7;
}
.final-copy-btn {
  margin-top: 12px; background: var(--teal); color: white;
  border: none; border-radius: 8px; padding: 10px 20px;
  font-family: 'DM Sans', sans-serif; font-size: 14px; font-weight: 700;
  cursor: pointer; width: 100%;
}
.final-copy-btn:hover { background: var(--teal-dark); }

.divider { border: none; border-top: 1px solid var(--teal-light); margin: 16px 0; }

.progress-bar-wrap { margin-top: 12px; display: none; }
.progress-bar-bg { background: var(--border); border-radius: 99px; height: 6px; }
.progress-bar-fill { background: var(--teal); height: 6px; border-radius: 99px; width: 0%; transition: width 0.3s; }
.progress-text { font-size: 12px; color: var(--mid); margin-top: 6px; }
</style>
</head>
<body>

<div class="header">
  <div class="header-logo">Q</div>
  <div>
    <div class="header-title">Q-Mart Product Manager</div>
    <div class="header-sub">Format desc · Upload images · Copy sheet row</div>
  </div>
</div>

<div class="container">

  <!-- STEP 1: PRODUCT INFO -->
  <div class="section-title">Step 1 — Product Details</div>
  <div class="card">
    <div class="row2" style="margin-bottom:16px;">
      <div>
        <label>Product Name</label>
        <input type="text" id="productName" placeholder="e.g. Nokia 6300">
      </div>
      <div>
        <label>Price (QAR)</label>
        <input type="number" id="productPrice" placeholder="e.g. 139">
      </div>
    </div>
    <div>
      <label>Category</label>
      <select id="productCategory">
        <option value="">— Select —</option>
        <option>Appliances</option>
        <option>Phones &amp; Accessories</option>
        <option>Islamic Products</option>
        <option>Electronics</option>
        <option>Home &amp; Kitchen</option>
        <option>Tools &amp; Equipment</option>
        <option>Personal Care</option>
        <option>Clothing &amp; Fashion</option>
        <option>Food &amp; Grocery</option>
        <option>Other</option>
      </select>
    </div>
  </div>

  <!-- STEP 2: DESCRIPTION -->
  <div class="section-title">Step 2 — Description</div>
  <div class="card">
    <div class="tip" style="margin-bottom:16px;">
      <strong>How it works:</strong> Paste raw description — AI formats it as:<br>
      <span style="margin-top:6px;display:block;font-family:monospace;font-size:12px;color:var(--dark);">
        Intro sentence <span class="pipe">|</span> Feature 1 <span class="pipe">|</span> Feature 2 <span class="pipe">|</span> Feature 3...
      </span>
    </div>
    <label>Raw Product Description</label>
    <textarea id="inputDesc" rows="8" placeholder="Paste your raw product description here — emojis, bullets, checkmarks, anything. AI will clean it up."></textarea>
    <div class="btn-row">
      <button class="btn" id="formatBtn" onclick="formatDesc()">
        <svg width="15" height="15" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path d="M12 2l3.09 6.26L22 9.27l-5 4.87 1.18 6.88L12 17.77l-6.18 3.25L7 14.14 2 9.27l6.91-1.01L12 2z"/></svg>
        Format with AI
      </button>
      <button class="btn btn-ghost" onclick="clearDesc()">Clear</button>
    </div>

    <div class="loading" id="descLoading"><div class="spinner"></div> Formatting...</div>
    <div class="error-box" id="descError"></div>

    <div class="result-box" id="descResult">
      <div class="result-label">Formatted Description</div>
      <div class="result-text" id="resultText"></div>
      <div style="margin-top:6px;">
        <button class="copy-btn" id="copyDescBtn" onclick="copyField('resultText','copyDescBtn','Copy')">Copy</button>
        <button class="copy-btn" onclick="editDesc()" style="background:var(--mid);margin-left:8px;">Edit</button>
      </div>
      <hr class="divider">
      <div class="result-label">Suggested Category</div>
      <div class="result-text" id="categoryText" style="font-size:15px;font-weight:700;color:var(--teal-dark);"></div>
      <button class="copy-btn" onclick="applySuggestedCategory()" style="margin-top:8px;">Use this Category</button>
    </div>

    <!-- manual desc edit area -->
    <div id="descEditArea" style="display:none;margin-top:14px;">
      <label>Edit Formatted Description</label>
      <textarea id="descEditInput" rows="4"></textarea>
      <button class="btn" style="margin-top:10px;font-size:13px;padding:9px 18px;" onclick="saveDescEdit()">Save</button>
    </div>
  </div>

  <!-- STEP 3: IMAGES -->
  <div class="section-title">Step 3 — Images</div>
  <div class="card">
    <div class="auth-bar" id="authBar">
      <div class="auth-dot" id="authDot"></div>
      <div class="auth-text" id="authText">Not connected to Google Drive</div>
      <button class="auth-btn" id="authBtn" onclick="handleAuth()">Connect</button>
    </div>

    <div class="upload-zone" id="uploadZone" onclick="document.getElementById('fileInput').click()">
      <svg width="32" height="32" fill="none" stroke="currentColor" stroke-width="1.5" viewBox="0 0 24 24"><path d="M21 15v4a2 2 0 01-2 2H5a2 2 0 01-2-2v-4"/><polyline points="17 8 12 3 7 8"/><line x1="12" y1="3" x2="12" y2="15"/></svg>
      <p>Tap to select images</p>
      <span>Select multiple at once — JPG, PNG, WEBP</span>
    </div>
    <input type="file" id="fileInput" accept="image/*" multiple style="display:none" onchange="handleFiles(this.files)">

    <div class="preview-grid" id="previewGrid"></div>

    <div class="progress-bar-wrap" id="progressWrap">
      <div class="progress-bar-bg"><div class="progress-bar-fill" id="progressFill"></div></div>
      <div class="progress-text" id="progressText"></div>
    </div>

    <div class="btn-row">
      <button class="btn" id="uploadBtn" onclick="uploadAll()" style="display:none;">
        <svg width="15" height="15" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path d="M21 15v4a2 2 0 01-2 2H5a2 2 0 01-2-2v-4"/><polyline points="17 8 12 3 7 8"/><line x1="12" y1="3" x2="12" y2="15"/></svg>
        Upload to Drive
      </button>
      <button class="btn btn-ghost" onclick="clearImages()" id="clearImgBtn" style="display:none;">Clear</button>
    </div>

    <div class="error-box" id="imgError"></div>

    <div class="result-box" id="imgResult" style="margin-top:16px;">
      <div class="result-label">Drive Links (comma separated)</div>
      <div class="result-text" id="imgLinks"></div>
      <button class="copy-btn" id="copyImgBtn" onclick="copyField('imgLinks','copyImgBtn','Copy Links')">Copy Links</button>
    </div>
  </div>

  <!-- STEP 4: SHEET ROW -->
  <div class="section-title">Step 4 — Sheet Row</div>
  <div class="card">
    <div class="tip">
      <strong>Final step:</strong> Enter the next row ID, then generate your complete Google Sheet row — ready to paste.
    </div>
    <div style="margin-top:14px;">
      <label>Row ID (next number in your sheet)</label>
      <input type="number" id="rowId" placeholder="e.g. 6" style="max-width:160px;">
    </div>
    <button class="btn" style="margin-top:14px;" onclick="generateRow()">
      <svg width="15" height="15" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><rect x="3" y="3" width="18" height="18" rx="2"/><path d="M3 9h18M9 21V9"/></svg>
      Generate Sheet Row
    </button>
    <div class="error-box" id="rowError"></div>
    <div class="final-row-box" id="finalRowBox">
      <div class="final-row-label">Your Sheet Row — paste into Google Sheets</div>
      <div class="final-row-text" id="finalRowText"></div>
      <button class="final-copy-btn" id="finalCopyBtn" onclick="copyFinalRow()">Copy Sheet Row</button>
    </div>
  </div>

</div>

<script src="https://apis.google.com/js/api.js"></script>
<script>

const GROQ_API_KEY = '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';
const GDRIVE_CLIENT_ID = '242818705775-t3nbu3pq1ml2ek35ss89mepdl22n3utr.apps.googleusercontent.com';
const GDRIVE_SCOPE = 'https://www.googleapis.com/auth/drive.file';
const FOLDER_NAME = 'QMart_Images';

let accessToken = null;
let folderId = null;
let selectedFiles = [];
let uploadedLinks = [];
let formattedDesc = '';
let suggestedCategory = '';

// ── GOOGLE AUTH ──────────────────────────────────────────────
function handleAuth() {
  if (accessToken) { signOut(); return; }
  const client = google.accounts.oauth2.initTokenClient({
    client_id: GDRIVE_CLIENT_ID,
    scope: GDRIVE_SCOPE,
    callback: (resp) => {
      if (resp.error) { showImgError('Auth failed: ' + resp.error); return; }
      accessToken = resp.access_token;
      setAuthConnected();
    }
  });
  client.requestAccessToken();
}

function setAuthConnected() {
  document.getElementById('authDot').classList.add('connected');
  document.getElementById('authText').textContent = 'Connected to Google Drive';
  document.getElementById('authBtn').textContent = 'Disconnect';
}

function signOut() {
  google.accounts.oauth2.revoke(accessToken, () => {});
  accessToken = null;
  folderId = null;
  document.getElementById('authDot').classList.remove('connected');
  document.getElementById('authText').textContent = 'Not connected to Google Drive';
  document.getElementById('authBtn').textContent = 'Connect';
}

// ── FILE HANDLING ────────────────────────────────────────────
function handleFiles(files) {
  for (const f of files) {
    if (!f.type.startsWith('image/')) continue;
    selectedFiles.push(f);
    addPreview(f, selectedFiles.length - 1);
  }
  if (selectedFiles.length > 0) {
    document.getElementById('uploadBtn').style.display = 'inline-flex';
    document.getElementById('clearImgBtn').style.display = 'inline-flex';
  }
}

function addPreview(file, idx) {
  const grid = document.getElementById('previewGrid');
  const div = document.createElement('div');
  div.className = 'preview-item';
  div.id = 'preview-' + idx;
  const img = document.createElement('img');
  img.src = URL.createObjectURL(file);
  const rm = document.createElement('button');
  rm.className = 'remove-btn';
  rm.textContent = '×';
  rm.onclick = (e) => { e.stopPropagation(); removeFile(idx); };
  const status = document.createElement('div');
  status.className = 'img-status';
  status.id = 'status-' + idx;
  status.textContent = 'Ready';
  div.appendChild(img); div.appendChild(rm); div.appendChild(status);
  grid.appendChild(div);
}

function removeFile(idx) {
  selectedFiles[idx] = null;
  const el = document.getElementById('preview-' + idx);
  if (el) el.remove();
  const active = selectedFiles.filter(f => f !== null);
  if (active.length === 0) {
    document.getElementById('uploadBtn').style.display = 'none';
    document.getElementById('clearImgBtn').style.display = 'none';
  }
}

function clearImages() {
  selectedFiles = [];
  uploadedLinks = [];
  document.getElementById('previewGrid').innerHTML = '';
  document.getElementById('uploadBtn').style.display = 'none';
  document.getElementById('clearImgBtn').style.display = 'none';
  document.getElementById('imgResult').style.display = 'none';
  document.getElementById('progressWrap').style.display = 'none';
  document.getElementById('imgError').style.display = 'none';
}

// drag and drop
const zone = document.getElementById('uploadZone');
zone.addEventListener('dragover', e => { e.preventDefault(); zone.classList.add('dragover'); });
zone.addEventListener('dragleave', () => zone.classList.remove('dragover'));
zone.addEventListener('drop', e => { e.preventDefault(); zone.classList.remove('dragover'); handleFiles(e.dataTransfer.files); });

// ── DRIVE UPLOAD ─────────────────────────────────────────────
async function uploadAll() {
  if (!accessToken) { showImgError('Connect to Google Drive first.'); return; }
  const files = selectedFiles.filter(f => f !== null);
  if (files.length === 0) { showImgError('No images selected.'); return; }

  document.getElementById('imgError').style.display = 'none';
  document.getElementById('imgResult').style.display = 'none';
  document.getElementById('uploadBtn').disabled = true;
  const progressWrap = document.getElementById('progressWrap');
  const progressFill = document.getElementById('progressFill');
  const progressText = document.getElementById('progressText');
  progressWrap.style.display = 'block';
  uploadedLinks = [];

  try {
    if (!folderId) folderId = await getOrCreateFolder();
  } catch(e) {
    showImgError('Could not access Drive folder: ' + e.message);
    document.getElementById('uploadBtn').disabled = false;
    return;
  }

  let done = 0;
  for (let i = 0; i < selectedFiles.length; i++) {
    const f = selectedFiles[i];
    if (!f) continue;
    const statusEl = document.getElementById('status-' + i);
    if (statusEl) { statusEl.textContent = 'Uploading...'; statusEl.className = 'img-status'; }
    try {
      const link = await uploadFile(f);
      uploadedLinks.push(link);
      done++;
      if (statusEl) { statusEl.textContent = 'Done'; statusEl.className = 'img-status done'; }
    } catch(e) {
      if (statusEl) { statusEl.textContent = 'Failed'; statusEl.className = 'img-status err'; }
    }
    const pct = Math.round((done / files.length) * 100);
    progressFill.style.width = pct + '%';
    progressText.textContent = done + ' of ' + files.length + ' uploaded';
  }

  document.getElementById('uploadBtn').disabled = false;

  if (uploadedLinks.length > 0) {
    document.getElementById('imgLinks').textContent = uploadedLinks.join(', ');
    document.getElementById('imgResult').style.display = 'block';
  } else {
    showImgError('All uploads failed. Check Drive connection.');
  }
}

async function getOrCreateFolder() {
  // search for existing folder
  const search = await gdriveRequest('GET',
    `https://www.googleapis.com/drive/v3/files?q=name='${FOLDER_NAME}' and mimeType='application/vnd.google-apps.folder' and trashed=false&fields=files(id)`
  );
  if (search.files && search.files.length > 0) return search.files[0].id;

  // create folder
  const created = await gdriveRequest('POST', 'https://www.googleapis.com/drive/v3/files', {
    name: FOLDER_NAME,
    mimeType: 'application/vnd.google-apps.folder'
  });
  return created.id;
}

async function uploadFile(file) {
  // multipart upload
  const meta = { name: file.name, parents: [folderId] };
  const boundary = 'qmart_boundary_' + Date.now();
  const metaStr = JSON.stringify(meta);
  const fileData = await readFileAsArrayBuffer(file);

  const encoder = new TextEncoder();
  const metaPart = encoder.encode(
    '--' + boundary + '\r\nContent-Type: application/json; charset=UTF-8\r\n\r\n' + metaStr + '\r\n'
  );
  const filePart = encoder.encode('--' + boundary + '\r\nContent-Type: ' + file.type + '\r\n\r\n');
  const endPart = encoder.encode('\r\n--' + boundary + '--');

  const body = new Uint8Array(metaPart.length + filePart.length + fileData.byteLength + endPart.length);
  body.set(metaPart, 0);
  body.set(filePart, metaPart.length);
  body.set(new Uint8Array(fileData), metaPart.length + filePart.length);
  body.set(endPart, metaPart.length + filePart.length + fileData.byteLength);

  const resp = await fetch('https://www.googleapis.com/upload/drive/v3/files?uploadType=multipart&fields=id', {
    method: 'POST',
    headers: {
      'Authorization': 'Bearer ' + accessToken,
      'Content-Type': 'multipart/related; boundary=' + boundary
    },
    body
  });
  if (!resp.ok) throw new Error('Upload failed');
  const data = await resp.json();
  const fileId = data.id;

  // make public
  await gdriveRequest('POST', `https://www.googleapis.com/drive/v3/files/${fileId}/permissions`, {
    role: 'reader', type: 'anyone'
  });

  return `https://drive.google.com/file/d/${fileId}/view`;
}

function readFileAsArrayBuffer(file) {
  return new Promise((res, rej) => {
    const r = new FileReader();
    r.onload = () => res(r.result);
    r.onerror = () => rej(new Error('Read failed'));
    r.readAsArrayBuffer(file);
  });
}

async function gdriveRequest(method, url, body) {
  const opts = {
    method,
    headers: { 'Authorization': 'Bearer ' + accessToken, 'Content-Type': 'application/json' }
  };
  if (body) opts.body = JSON.stringify(body);
  const resp = await fetch(url, opts);
  if (!resp.ok) {
    const err = await resp.json().catch(() => ({}));
    throw new Error(err.error?.message || resp.statusText);
  }
  return resp.json();
}

// ── DESCRIPTION ──────────────────────────────────────────────
function clearDesc() {
  document.getElementById('inputDesc').value = '';
  document.getElementById('descResult').style.display = 'none';
  document.getElementById('descError').style.display = 'none';
  document.getElementById('descEditArea').style.display = 'none';
  formattedDesc = '';
  suggestedCategory = '';
}

function editDesc() {
  document.getElementById('descEditInput').value = formattedDesc;
  document.getElementById('descEditArea').style.display = 'block';
  document.getElementById('descEditInput').focus();
}

function saveDescEdit() {
  formattedDesc = document.getElementById('descEditInput').value.trim();
  document.getElementById('resultText').textContent = formattedDesc;
  document.getElementById('descEditArea').style.display = 'none';
}

function applySuggestedCategory() {
  if (!suggestedCategory) return;
  const sel = document.getElementById('productCategory');
  for (const opt of sel.options) {
    if (opt.value === suggestedCategory) { sel.value = suggestedCategory; return; }
  }
}

async function formatDesc() {
  const input = document.getElementById('inputDesc').value.trim();
  if (!input) { showDescError('Paste a description first.'); return; }

  const btn = document.getElementById('formatBtn');
  const loading = document.getElementById('descLoading');
  btn.disabled = true;
  loading.style.display = 'flex';
  document.getElementById('descError').style.display = 'none';
  document.getElementById('descResult').style.display = 'none';

  const systemPrompt = `You are a product description formatter for Q-Mart, Doha, Qatar.

Return a JSON object with exactly two keys:
1. "desc" — formatted description
2. "category" — detected product category

For "desc":
[Full intro — keep all detail, remove emojis] | [Feature 1] | [Feature 2] | [Feature 3] ...
- ONE single line, no line breaks
- Keep all specs, model numbers, sizes exactly
- Remove only emojis and bullet symbols (✅ ✔ • ▪ etc.)
- Use ONLY | as separator

For "category" — pick one:
Appliances | Phones & Accessories | Islamic Products | Electronics | Home & Kitchen | Tools & Equipment | Personal Care | Clothing & Fashion | Food & Grocery | Other

Return ONLY raw JSON, no markdown, no backticks.
Example: {"desc":"Full text here","category":"Appliances"}`;

  try {
    const response = await fetch('https://api.groq.com/openai/v1/chat/completions', {
      method: 'POST',
      headers: { 'Content-Type': 'application/json', 'Authorization': 'Bearer ' + GROQ_API_KEY },
      body: JSON.stringify({
        model: 'llama-3.3-70b-versatile',
        max_tokens: 2000,
        temperature: 0.1,
        messages: [
          { role: 'system', content: systemPrompt },
          { role: 'user', content: input }
        ]
      })
    });
    const data = await response.json();
    if (data.error) throw new Error(data.error.message);
    const raw = data.choices?.[0]?.message?.content?.trim();
    if (!raw) throw new Error('No result returned.');
    let parsed;
    try { parsed = JSON.parse(raw); }
    catch(e) {
      const match = raw.match(/\{[\s\S]*\}/);
      if (match) parsed = JSON.parse(match[0]);
      else throw new Error('Could not parse AI response.');
    }
    formattedDesc = parsed.desc || '';
    suggestedCategory = parsed.category || '';
    document.getElementById('resultText').textContent = formattedDesc;
    document.getElementById('categoryText').textContent = suggestedCategory;
    document.getElementById('descResult').style.display = 'block';
  } catch(err) {
    showDescError('Error: ' + err.message);
  } finally {
    btn.disabled = false;
    loading.style.display = 'none';
  }
}

// ── SHEET ROW ────────────────────────────────────────────────
function generateRow() {
  const id = document.getElementById('rowId').value.trim();
  const name = document.getElementById('productName').value.trim();
  const price = document.getElementById('productPrice').value.trim();
  const category = document.getElementById('productCategory').value.trim();
  const desc = formattedDesc || document.getElementById('resultText').textContent.trim();
  const images = uploadedLinks.length > 0
    ? uploadedLinks.join(', ')
    : document.getElementById('imgLinks').textContent.trim();

  const missing = [];
  if (!id) missing.push('Row ID');
  if (!name) missing.push('Product Name');
  if (!price) missing.push('Price');
  if (!category) missing.push('Category');
  if (!desc) missing.push('Description (format it first)');
  if (!images) missing.push('Images (upload first)');

  if (missing.length) {
    document.getElementById('rowError').textContent = 'Missing: ' + missing.join(', ');
    document.getElementById('rowError').style.display = 'block';
    return;
  }
  document.getElementById('rowError').style.display = 'none';

  const row = `${id}\t${name}\t${desc}\t${price}\t${category}\t${images}`;
  document.getElementById('finalRowText').textContent = row;
  document.getElementById('finalRowBox').style.display = 'block';
}

function copyFinalRow() {
  const text = document.getElementById('finalRowText').textContent;
  const btn = document.getElementById('finalCopyBtn');
  copyText(text, () => {
    btn.textContent = 'Copied!';
    setTimeout(() => btn.textContent = 'Copy Sheet Row', 2000);
  });
}

// ── UTILS ────────────────────────────────────────────────────
function copyField(textId, btnId, defaultLabel) {
  const text = document.getElementById(textId).textContent.trim();
  const btn = document.getElementById(btnId);
  if (!text) return;
  copyText(text, () => {
    btn.textContent = 'Copied!';
    setTimeout(() => btn.textContent = defaultLabel, 2000);
  });
}

function copyText(text, onDone) {
  try {
    navigator.clipboard.writeText(text).then(onDone).catch(() => fallbackCopy(text, onDone));
  } catch(e) { fallbackCopy(text, onDone); }
}

function fallbackCopy(text, onDone) {
  const ta = document.createElement('textarea');
  ta.value = text; ta.style.position = 'fixed'; ta.style.opacity = '0';
  document.body.appendChild(ta); ta.focus(); ta.select();
  document.execCommand('copy'); document.body.removeChild(ta);
  if (onDone) onDone();
}

function showDescError(msg) {
  const el = document.getElementById('descError');
  el.textContent = msg; el.style.display = 'block';
}
function showImgError(msg) {
  const el = document.getElementById('imgError');
  el.textContent = msg; el.style.display = 'block';
}

// load GIS library
const gisScript = document.createElement('script');
gisScript.src = 'https://accounts.google.com/gsi/client';
document.head.appendChild(gisScript);
</script>
</body>
</html>

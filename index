{\rtf1\ansi\ansicpg1252\cocoartf2822
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 \
<style>\
*\{box-sizing:border-box;margin:0;padding:0\}\
body\{font-family:var(--font-sans);font-size:14px;color:var(--color-text-primary);background:transparent\}\
h2\{font-size:18px;font-weight:500;margin-bottom:1rem;color:var(--color-text-primary)\}\
h3\{font-size:15px;font-weight:500;margin-bottom:.75rem;color:var(--color-text-primary)\}\
.section\{background:var(--color-background-primary);border:0.5px solid var(--color-border-tertiary);border-radius:var(--border-radius-lg);padding:1.25rem;margin-bottom:1rem\}\
.grid2\{display:grid;grid-template-columns:1fr 1fr;gap:12px\}\
.grid3\{display:grid;grid-template-columns:1fr 1fr 1fr;gap:12px\}\
.grid4\{display:grid;grid-template-columns:1fr 1fr 1fr 1fr;gap:12px\}\
.field\{display:flex;flex-direction:column;gap:4px\}\
.field label\{font-size:12px;color:var(--color-text-secondary)\}\
.field input[type=range]\{width:100%\}\
.val-row\{display:flex;justify-content:space-between;align-items:center;font-size:12px;color:var(--color-text-secondary);margin-bottom:2px\}\
.metric-card\{background:var(--color-background-secondary);border-radius:var(--border-radius-md);padding:.75rem 1rem\}\
.metric-card .label\{font-size:11px;color:var(--color-text-secondary);margin-bottom:4px;text-transform:uppercase;letter-spacing:.04em\}\
.metric-card .value\{font-size:22px;font-weight:500;color:var(--color-text-primary)\}\
.metric-card .sub\{font-size:11px;color:var(--color-text-tertiary);margin-top:2px\}\
.ins-bar\{height:16px;border-radius:4px;display:flex;overflow:hidden;margin:8px 0\}\
.ins-bar span\{height:100%;transition:width .3s\}\
.tag\{display:inline-flex;align-items:center;gap:6px;font-size:12px;padding:3px 8px;border-radius:var(--border-radius-md);border:0.5px solid var(--color-border-tertiary);cursor:pointer;user-select:none;transition:background .15s\}\
.tag.on\{background:var(--color-background-info);color:var(--color-text-info);border-color:var(--color-border-info)\}\
.tag-wrap\{display:flex;flex-wrap:wrap;gap:6px;margin-top:6px\}\
.cpt-table\{width:100%;border-collapse:collapse;font-size:12px\}\
.cpt-table th\{text-align:left;font-weight:500;font-size:11px;color:var(--color-text-secondary);padding:6px 8px;border-bottom:0.5px solid var(--color-border-tertiary);text-transform:uppercase;letter-spacing:.04em\}\
.cpt-table td\{padding:5px 8px;border-bottom:0.5px solid var(--color-border-tertiary);color:var(--color-text-primary)\}\
.cpt-table tr:last-child td\{border-bottom:none\}\
.cpt-table .num\{text-align:right\}\
.total-row\{background:var(--color-background-secondary);font-weight:500\}\
.warn\{font-size:11px;color:var(--color-text-warning);margin-top:4px\}\
.divider\{border:none;border-top:0.5px solid var(--color-border-tertiary);margin:1rem 0\}\
.ins-legend\{display:flex;gap:12px;font-size:11px;margin-top:4px\}\
.ins-legend span\{display:flex;align-items:center;gap:4px\}\
.dot\{width:8px;height:8px;border-radius:50%;flex-shrink:0\}\
select\{padding:6px 8px;border:0.5px solid var(--color-border-secondary);border-radius:var(--border-radius-md);background:var(--color-background-primary);color:var(--color-text-primary);font-size:13px;width:100%\}\
input[type=number]\{padding:6px 8px;border:0.5px solid var(--color-border-secondary);border-radius:var(--border-radius-md);background:var(--color-background-primary);color:var(--color-text-primary);font-size:13px;width:100%\}\
.section-title\{display:flex;align-items:center;gap:8px;margin-bottom:1rem\}\
.pill\{font-size:10px;padding:2px 7px;background:var(--color-background-info);color:var(--color-text-info);border-radius:10px;font-weight:500\}\
.cash-item\{display:flex;justify-content:space-between;align-items:center;padding:6px 0;border-bottom:0.5px solid var(--color-border-tertiary)\}\
.cash-item:last-child\{border-bottom:none\}\
.cash-item label\{font-size:13px\}\
.cash-item input\{width:80px;text-align:right\}\
@media(max-width:600px)\{.grid2,.grid3,.grid4\{grid-template-columns:1fr\}\}\
</style>\
\
<div style="padding:1rem 0">\
\
<div style="display:flex;align-items:baseline;gap:12px;margin-bottom:1.5rem">\
  <h2 style="margin:0">Ophthalmology revenue estimator</h2>\
  <span style="font-size:12px;color:var(--color-text-tertiary)"> \'b7 Dr. X</span>\
</div>\
\
<div class="section">\
  <div class="section-title"><h3 style="margin:0">Practice schedule</h3></div>\
  <div class="grid3">\
    <div class="field">\
      <label>Patients per clinic day</label>\
      <div class="val-row"><span>5</span><span id="ppd-val" style="font-weight:500;color:var(--color-text-primary)">25</span><span>60</span></div>\
      <input type="range" id="ppd" min="5" max="60" value="25" step="1" oninput="upd()">\
    </div>\
    <div class="field">\
      <label>Clinic days per week</label>\
      <div class="val-row"><span>1</span><span id="cpw-val" style="font-weight:500;color:var(--color-text-primary)">4</span><span>5</span></div>\
      <input type="range" id="cpw" min="1" max="5" value="4" step="1" oninput="upd()">\
    </div>\
    <div class="field">\
      <label>Surgery days per month</label>\
      <div class="val-row"><span>0</span><span id="sdm-val" style="font-weight:500;color:var(--color-text-primary)">4</span><span>16</span></div>\
      <input type="range" id="sdm" min="0" max="16" value="4" step="1" oninput="upd()">\
    </div>\
  </div>\
  <p id="sched-note" class="warn" style="margin-top:8px"></p>\
</div>\
\
<div class="section">\
  <div class="section-title"><h3 style="margin:0">Insurance mix</h3><span class="pill">must total 100%</span></div>\
  <div class="grid4">\
    <div class="field">\
      <label>Medicare %</label>\
      <div class="val-row"><span>0</span><span id="mc-val" style="font-weight:500;color:var(--color-text-primary)">35</span><span>100</span></div>\
      <input type="range" id="mc" min="0" max="100" value="35" step="1" oninput="syncIns('mc')">\
    </div>\
    <div class="field">\
      <label>Medicaid %</label>\
      <div class="val-row"><span>0</span><span id="md-val" style="font-weight:500;color:var(--color-text-primary)">30</span><span>100</span></div>\
      <input type="range" id="md" min="0" max="100" value="30" step="1" oninput="syncIns('md')">\
    </div>\
    <div class="field">\
      <label>Commercial %</label>\
      <div class="val-row"><span>0</span><span id="com-val" style="font-weight:500;color:var(--color-text-primary)">30</span><span>100</span></div>\
      <input type="range" id="com" min="0" max="100" value="30" step="1" oninput="syncIns('com')">\
    </div>\
    <div class="field">\
      <label>Self-pay %</label>\
      <div class="val-row"><span>0</span><span id="sp-val" style="font-weight:500;color:var(--color-text-primary)">5</span><span>100</span></div>\
      <input type="range" id="sp" min="0" max="100" value="5" step="1" oninput="syncIns('sp')">\
    </div>\
  </div>\
  <div class="ins-bar" id="ins-bar">\
    <span style="width:35%;background:#378ADD"></span>\
    <span style="width:30%;background:#1D9E75"></span>\
    <span style="width:30%;background:#D85A30"></span>\
    <span style="width:5%;background:#888780"></span>\
  </div>\
  <div class="ins-legend">\
    <span><span class="dot" style="background:#378ADD"></span>Medicare</span>\
    <span><span class="dot" style="background:#1D9E75"></span>Medicaid</span>\
    <span><span class="dot" style="background:#D85A30"></span>Commercial</span>\
    <span><span class="dot" style="background:#888780"></span>Self-pay</span>\
  </div>\
  <p id="ins-warn" class="warn" style="margin-top:6px"></p>\
\
  <hr class="divider">\
  <div class="grid2">\
    <div class="field">\
      <label>Medicaid rate vs Medicare (%)</label>\
      <div class="val-row"><span>40%</span><span id="mdr-val" style="font-weight:500;color:var(--color-text-primary)">72%</span><span>120%</span></div>\
      <input type="range" id="mdr" min="40" max="120" value="72" step="1" oninput="upd()">\
      <span style="font-size:11px;color:var(--color-text-tertiary);margin-top:2px">Your state's Medicaid reimbursement as % of Medicare rate</span>\
    </div>\
    <div class="field">\
      <label>Commercial rate vs Medicare (%)</label>\
      <div class="val-row"><span>100%</span><span id="comr-val" style="font-weight:500;color:var(--color-text-primary)">130%</span><span>200%</span></div>\
      <input type="range" id="comr" min="100" max="200" value="130" step="1" oninput="upd()">\
      <span style="font-size:11px;color:var(--color-text-tertiary);margin-top:2px">Commercial contracts vs Medicare \'97 typically 110\'96150%</span>\
    </div>\
  </div>\
</div>\
\
<div class="section">\
  <div class="section-title"><h3 style="margin:0">Patient visit mix</h3></div>\
  <div class="grid3">\
    <div class="field">\
      <label>New patients %</label>\
      <div class="val-row"><span>5%</span><span id="np-val" style="font-weight:500;color:var(--color-text-primary)">22%</span><span>60%</span></div>\
      <input type="range" id="np" min="5" max="60" value="22" step="1" oninput="upd()">\
    </div>\
    <div class="field">\
      <label>Comprehensive exams (of established) %</label>\
      <div class="val-row"><span>10%</span><span id="comp-val" style="font-weight:500;color:var(--color-text-primary)">30%</span><span>80%</span></div>\
      <input type="range" id="comp" min="10" max="80" value="30" step="1" oninput="upd()">\
    </div>\
    <div class="field">\
      <label>Glaucoma/complex visit % (of established) </label>\
      <div class="val-row"><span>0%</span><span id="glauc-val" style="font-weight:500;color:var(--color-text-primary)">15%</span><span>50%</span></div>\
      <input type="range" id="glauc" min="0" max="50" value="15" step="1" oninput="upd()">\
    </div>\
  </div>\
</div>\
\
<div class="section">\
  <div class="section-title"><h3 style="margin:0">Surgery mix</h3><span class="pill">per surgery day</span></div>\
  <div class="grid2" style="margin-bottom:1rem">\
    <div class="field">\
      <label>Cases per surgery day</label>\
      <div class="val-row"><span>4</span><span id="cpsd-val" style="font-weight:500;color:var(--color-text-primary)">10</span><span>20</span></div>\
      <input type="range" id="cpsd" min="4" max="20" value="10" step="1" oninput="upd()">\
    </div>\
    <div></div>\
  </div>\
\
  <h3 style="font-size:13px;color:var(--color-text-secondary);margin-bottom:8px">Cataract surgery</h3>\
  <div class="grid3">\
    <div class="field">\
      <label>Standard cataract (66984) %</label>\
      <div class="val-row"><span>0%</span><span id="std-val" style="font-weight:500;color:var(--color-text-primary)">55%</span><span>100%</span></div>\
      <input type="range" id="std" min="0" max="100" value="55" step="1" oninput="upd()">\
    </div>\
    <div class="field">\
      <label>Complex cataract (66982) %</label>\
      <div class="val-row"><span>0%</span><span id="cplx-val" style="font-weight:500;color:var(--color-text-primary)">15%</span><span>100%</span></div>\
      <input type="range" id="cplx" min="0" max="100" value="15" step="1" oninput="upd()">\
    </div>\
    <div class="field">\
      <label>Premium cataract (66991) %</label>\
      <div class="val-row"><span>0%</span><span id="prem-val" style="font-weight:500;color:var(--color-text-primary)">10%</span><span>100%</span></div>\
      <input type="range" id="prem" min="0" max="100" value="10" step="1" oninput="upd()">\
    </div>\
  </div>\
  <p id="cat-warn" class="warn"></p>\
\
  <hr class="divider">\
  <h3 style="font-size:13px;color:var(--color-text-secondary);margin-bottom:8px">MIGS (minimally invasive glaucoma surgery)</h3>\
  <div class="grid4">\
    <div class="field">\
      <label>Stent-based (66991+) %</label>\
      <div class="val-row"><span>0</span><span id="stent-val" style="font-weight:500;color:var(--color-text-primary)">8%</span><span>50%</span></div>\
      <input type="range" id="stent" min="0" max="50" value="8" step="1" oninput="upd()">\
    </div>\
    <div class="field">\
      <label>Goniotomy (65820) %</label>\
      <div class="val-row"><span>0</span><span id="gonio-val" style="font-weight:500;color:var(--color-text-primary)">3%</span><span>30%</span></div>\
      <input type="range" id="gonio" min="0" max="30" value="3" step="1" oninput="upd()">\
    </div>\
    <div class="field">\
      <label>Canaloplasty (66174) %</label>\
      <div class="val-row"><span>0</span><span id="canal-val" style="font-weight:500;color:var(--color-text-primary)">2%</span><span>30%</span></div>\
      <input type="range" id="canal" min="0" max="30" value="2" step="1" oninput="upd()">\
    </div>\
    <div class="field">\
      <label>XEN gel stent (0449T) %</label>\
      <div class="val-row"><span>0</span><span id="xen-val" style="font-weight:500;color:var(--color-text-primary)">2%</span><span>30%</span></div>\
      <input type="range" id="xen" min="0" max="30" value="2" step="1" oninput="upd()">\
    </div>\
  </div>\
\
  <hr class="divider">\
  <h3 style="font-size:13px;color:var(--color-text-secondary);margin-bottom:8px">Other surgery</h3>\
  <div class="grid3">\
    <div class="field">\
      <label>SLT laser (65855) \'97 per surgery day</label>\
      <div class="val-row"><span>0</span><span id="slt2-val" style="font-weight:500;color:var(--color-text-primary)">1</span><span>6</span></div>\
      <input type="range" id="slt2" min="0" max="6" value="1" step="1" oninput="upd()">\
    </div>\
    <div class="field">\
      <label>YAG capsulotomy (66821) \'97 per surgery day</label>\
      <div class="val-row"><span>0</span><span id="yag-val" style="font-weight:500;color:var(--color-text-primary)">2</span><span>8</span></div>\
      <input type="range" id="yag" min="0" max="8" value="2" step="1" oninput="upd()">\
    </div>\
    <div class="field">\
      <label>LPI (66761) \'97 per surgery day</label>\
      <div class="val-row"><span>0</span><span id="lpi-val" style="font-weight:500;color:var(--color-text-primary)">0</span><span>4</span></div>\
      <input type="range" id="lpi" min="0" max="4" value="0" step="1" oninput="upd()">\
    </div>\
  </div>\
</div>\
\
<div class="section">\
  <div class="section-title"><h3 style="margin:0">In-clinic procedures</h3><span class="pill">per clinic day</span></div>\
  <div class="grid4">\
    <div class="field">\
      <label>OCT (92133/92134) /day</label>\
      <div class="val-row"><span>0</span><span id="oct-val" style="font-weight:500;color:var(--color-text-primary)">8</span><span>30</span></div>\
      <input type="range" id="oct" min="0" max="30" value="8" step="1" oninput="upd()">\
    </div>\
    <div class="field">\
      <label>Visual fields (92083) /day</label>\
      <div class="val-row"><span>0</span><span id="vf-val" style="font-weight:500;color:var(--color-text-primary)">5</span><span>20</span></div>\
      <input type="range" id="vf" min="0" max="20" value="5" step="1" oninput="upd()">\
    </div>\
    <div class="field">\
      <label>Punctal plugs (68761) /day</label>\
      <div class="val-row"><span>0</span><span id="plug-val" style="font-weight:500;color:var(--color-text-primary)">1</span><span>8</span></div>\
      <input type="range" id="plug" min="0" max="8" value="1" step="1" oninput="upd()">\
    </div>\
    <div class="field">\
      <label>Prokera (65778) /day</label>\
      <div class="val-row"><span>0</span><span id="prok-val" style="font-weight:500;color:var(--color-text-primary)">0</span><span>4</span></div>\
      <input type="range" id="prok" min="0" max="4" value="0" step="1" oninput="upd()">\
    </div>\
  </div>\
  <div class="grid3" style="margin-top:12px">\
    <div class="field">\
      <label>Biometry/IOL calc (92136) /clinic day</label>\
      <div class="val-row"><span>0</span><span id="bio-val" style="font-weight:500;color:var(--color-text-primary)">1</span><span>8</span></div>\
      <input type="range" id="bio" min="0" max="8" value="1" step="1" oninput="upd()">\
    </div>\
    <div class="field">\
      <label>Anterior segment photo /day</label>\
      <div class="val-row"><span>0</span><span id="asp-val" style="font-weight:500;color:var(--color-text-primary)">2</span><span>12</span></div>\
      <input type="range" id="asp" min="0" max="12" value="2" step="1" oninput="upd()">\
    </div>\
    <div class="field">\
      <label>Fluorescein angiography /day</label>\
      <div class="val-row"><span>0</span><span id="fa-val" style="font-weight:500;color:var(--color-text-primary)">0</span><span>4</span></div>\
      <input type="range" id="fa" min="0" max="4" value="0" step="1" oninput="upd()">\
    </div>\
  </div>\
</div>\
\
<div class="section">\
  <div class="section-title"><h3 style="margin:0">Cash-pay services</h3><span class="pill">self-pay / out-of-pocket</span></div>\
  <div class="grid2">\
    <div>\
      <div class="cash-item"><label>Femto laser (per eye)</label><input type="number" id="femto-price" value="800" min="0" oninput="upd()"><span style="font-size:11px;color:var(--color-text-tertiary);margin-left:6px">$ / eye</span></div>\
      <div class="cash-item"><label>Femto laser eyes per month</label><input type="number" id="femto-n" value="3" min="0" oninput="upd()"></div>\
      <div class="cash-item" style="margin-top:8px"><label>Vivity IOL (per eye)</label><input type="number" id="vivity-price" value="1200" min="0" oninput="upd()"></div>\
      <div class="cash-item"><label>Vivity eyes per month</label><input type="number" id="vivity-n" value="2" min="0" oninput="upd()"></div>\
      <div class="cash-item" style="margin-top:8px"><label>PanOptix IOL (per eye)</label><input type="number" id="panoptix-price" value="1200" min="0" oninput="upd()"></div>\
      <div class="cash-item"><label>PanOptix eyes per month</label><input type="number" id="panoptix-n" value="3" min="0" oninput="upd()"></div>\
    </div>\
    <div>\
      <div class="cash-item"><label>Prem. presbyopia IOL \'97 EnVista/other (per eye)</label><input type="number" id="envy-price" value="1000" min="0" oninput="upd()"></div>\
      <div class="cash-item"><label>Presbyopia IOL eyes per month</label><input type="number" id="envy-n" value="1" min="0" oninput="upd()"></div>\
      <div class="cash-item" style="margin-top:8px"><label>Toric IOL upgrade (per eye)</label><input type="number" id="toric-price" value="750" min="0" oninput="upd()"></div>\
      <div class="cash-item"><label>Toric eyes per month</label><input type="number" id="toric-n" value="2" min="0" oninput="upd()"></div>\
      <div class="cash-item" style="margin-top:8px"><label>LASIK/refractive consult fee</label><input type="number" id="lk-price" value="0" min="0" oninput="upd()"></div>\
      <div class="cash-item"><label>Refractive cases per month</label><input type="number" id="lk-n" value="0" min="0" oninput="upd()"></div>\
    </div>\
  </div>\
</div>\
\
<div class="section" style="background:var(--color-background-secondary)">\
  <h2>Monthly revenue estimate</h2>\
  <div class="grid4" style="margin-bottom:1rem">\
    <div class="metric-card">\
      <div class="label">Total monthly collections</div>\
      <div class="value" id="tot-col">\'97</div>\
      <div class="sub" id="tot-sub">\'97</div>\
    </div>\
    <div class="metric-card">\
      <div class="label">Clinic collections</div>\
      <div class="value" id="clinic-col">\'97</div>\
      <div class="sub" id="clinic-sub">\'97</div>\
    </div>\
    <div class="metric-card">\
      <div class="label">Surgery collections</div>\
      <div class="value" id="surg-col">\'97</div>\
      <div class="sub" id="surg-sub">\'97</div>\
    </div>\
    <div class="metric-card">\
      <div class="label">Cash-pay revenue</div>\
      <div class="value" id="cash-col">\'97</div>\
      <div class="sub">not insurance-adjusted</div>\
    </div>\
  </div>\
  <div class="grid3" style="margin-bottom:1.5rem">\
    <div class="metric-card">\
      <div class="label">Annual projection</div>\
      <div class="value" id="ann-col">\'97</div>\
      <div class="sub">12-month estimate</div>\
    </div>\
    <div class="metric-card">\
      <div class="label">Clinic days/month</div>\
      <div class="value" id="clinic-days-v">\'97</div>\
      <div class="sub">after surgery days subtracted</div>\
    </div>\
    <div class="metric-card">\
      <div class="label">Total monthly patients</div>\
      <div class="value" id="tot-pts">\'97</div>\
      <div class="sub">clinic visits</div>\
    </div>\
  </div>\
\
  <h3 style="margin-bottom:.75rem">Monthly collections breakdown by CPT</h3>\
  <table class="cpt-table">\
    <thead>\
      <tr>\
        <th>CPT</th>\
        <th>Description</th>\
        <th>Avg Medicare rate</th>\
        <th class="num">Monthly units</th>\
        <th class="num">Blended rate</th>\
        <th class="num">Est. collections</th>\
      </tr>\
    </thead>\
    <tbody id="cpt-body"></tbody>\
  </table>\
\
  <hr class="divider">\
  <h3 style="margin-bottom:.75rem">Cash-pay breakdown</h3>\
  <table class="cpt-table">\
    <thead>\
      <tr><th>Service</th><th class="num">Monthly units</th><th class="num">Price / unit</th><th class="num">Monthly revenue</th></tr>\
    </thead>\
    <tbody id="cash-body"></tbody>\
  </table>\
\
  <p style="font-size:11px;color:var(--color-text-tertiary);margin-top:1rem">Estimates based on 2025 Medicare physician fee schedule (national average). Commercial = Medicare \'d7 commercial rate multiplier. Medicaid = Medicare \'d7 Medicaid rate. Collections include standard adjustments. Cash-pay figures are gross and not insurance-adjusted. This is an estimate only \'97 actual collections vary by payer contract, geography, and documentation.</p>\
</div>\
\
</div>\
\
<script>\
const MC_RATES = \{\
  '99213': 78, '99214': 115, '92014': 175, '92004': 199, '92012': 92,\
  '92002': 143, '92133': 45, '92134': 47, '92083': 50, '68761': 183,\
  '65778': 557, '66984': 713, '66982': 919, '66991': 791,\
  '65820': 350, '66174': 539, '0449T': 420, '66821': 252,\
  '65855': 188, '66761': 195, '92136': 101, '92250': 25, '76514': 34,\
  '92082': 30\
\};\
\
const INS = ['mc','md','com','sp'];\
let lastChanged = 'sp';\
\
function syncIns(changed) \{\
  lastChanged = changed;\
  let vals = \{\};\
  INS.forEach(k => vals[k] = parseInt(document.getElementById(k).value));\
  let total = INS.reduce((s,k) => s+vals[k], 0);\
  document.getElementById('ins-warn').textContent = total === 100 ? '' : `Insurance mix totals $\{total\}% \'97 should be 100%`;\
  INS.forEach(k => \{\
    document.getElementById(k+'-val').textContent = vals[k]+'%';\
  \});\
  const colors = ['#378ADD','#1D9E75','#D85A30','#888780'];\
  const bar = document.getElementById('ins-bar');\
  bar.querySelectorAll('span').forEach((el,i) => \{ el.style.width = vals[INS[i]]+'%'; \});\
  upd();\
\}\
\
function sv(id)\{ return parseFloat(document.getElementById(id).value)||0; \}\
function ni(id)\{ return parseInt(document.getElementById(id).value)||0; \}\
\
function blended(mcare_rate) \{\
  let mc = sv('mc')/100, md = sv('md')/100, com = sv('com')/100, sp_pct = sv('sp')/100;\
  let mdr = sv('mdr')/100, comr = sv('comr')/100;\
  return mcare_rate*(mc*1 + md*mdr + com*comr + sp_pct*0.15);\
\}\
\
function fmt(n)\{ return '$'+Math.round(n).toLocaleString(); \}\
function fmtk(n)\{ \
  if(n>=1000000) return '$'+(n/1000000).toFixed(2)+'M';\
  if(n>=1000) return '$'+Math.round(n/1000)+'K';\
  return '$'+Math.round(n); \
\}\
\
function upd() \{\
  INS.forEach(k => document.getElementById(k+'-val').textContent = sv(k)+'%');\
  ['ppd','cpw','sdm','cpsd','np','comp','glauc','mdr','comr','std','cplx','prem','stent','gonio','canal','xen','slt2','yag','lpi','oct','vf','plug','prok','bio','asp','fa'].forEach(id => \{\
    const el = document.getElementById(id+'-val');\
    if(el) \{\
      const v = sv(id);\
      if(['mdr','comr'].includes(id)) el.textContent = v+'%';\
      else if(['np','comp','glauc','std','cplx','prem','stent','gonio','canal','xen'].includes(id)) el.textContent = v+'%';\
      else el.textContent = v;\
    \}\
  \});\
\
  const ppd=sv('ppd'), cpw=sv('cpw'), sdm=sv('sdm');\
  const weeksPerMonth = 4.33;\
  const clinicDaysPerWeek = cpw;\
  const totalDaysPerMonth = Math.round(clinicDaysPerWeek * weeksPerMonth);\
  const clinicDaysPerMonth = Math.max(0, totalDaysPerMonth - sdm);\
  document.getElementById('clinic-days-v').textContent = clinicDaysPerMonth;\
\
  const note = sdm > totalDaysPerMonth ? `Warning: $\{sdm\} surgery days exceeds $\{totalDaysPerMonth\} total work days. Reduce surgery days.` :\
    `$\{clinicDaysPerMonth\} clinic days + $\{sdm\} surgery days = $\{totalDaysPerMonth\} work days/month`;\
  document.getElementById('sched-note').textContent = note;\
\
  const totalPts = Math.round(ppd * clinicDaysPerMonth);\
  document.getElementById('tot-pts').textContent = totalPts.toLocaleString();\
\
  const np_pct = sv('np')/100;\
  const newPts = Math.round(totalPts * np_pct);\
  const estPts = totalPts - newPts;\
  const comp_pct = sv('comp')/100;\
  const glauc_pct = sv('glauc')/100;\
  const compExams = Math.round(estPts * comp_pct);\
  const glaucVisits = Math.round(estPts * glauc_pct);\
  const intExams = estPts - compExams - glaucVisits;\
\
  const cpsd = sv('cpsd');\
  const totalSurgCases = Math.round(cpsd * sdm);\
  const std_pct=sv('std')/100, cplx_pct=sv('cplx')/100, prem_pct=sv('prem')/100;\
  const stent_pct=sv('stent')/100, gonio_pct=sv('gonio')/100, canal_pct=sv('canal')/100, xen_pct=sv('xen')/100;\
  \
  const catWarn = (std_pct+cplx_pct+prem_pct)*100;\
  document.getElementById('cat-warn').textContent = catWarn > 100 ? `Cataract types total $\{Math.round(catWarn)\}% \'97 exceeds 100%` : '';\
\
  const stdN = Math.round(totalSurgCases * std_pct);\
  const cplxN = Math.round(totalSurgCases * cplx_pct);\
  const premN = Math.round(totalSurgCases * prem_pct);\
  const stentN = Math.round(totalSurgCases * stent_pct);\
  const gonioN = Math.round(totalSurgCases * gonio_pct);\
  const canalN = Math.round(totalSurgCases * canal_pct);\
  const xenN = Math.round(totalSurgCases * xen_pct);\
  const slt2N = Math.round(sv('slt2') * sdm);\
  const yagN = Math.round(sv('yag') * sdm);\
  const lpiN = Math.round(sv('lpi') * sdm);\
\
  const octN = Math.round(sv('oct') * clinicDaysPerMonth);\
  const vfN = Math.round(sv('vf') * clinicDaysPerMonth);\
  const plugN = Math.round(sv('plug') * clinicDaysPerMonth);\
  const prokN = Math.round(sv('prok') * clinicDaysPerMonth);\
  const bioN = Math.round(sv('bio') * clinicDaysPerMonth);\
  const aspN = Math.round(sv('asp') * clinicDaysPerMonth);\
  const faN = Math.round(sv('fa') * clinicDaysPerMonth);\
\
  const rows = [\
    \{cpt:'92002', desc:'New pt exam \'97 comprehensive', n:newPts, mc:MC_RATES['92002'], cat:'clinic'\},\
    \{cpt:'92014', desc:'Established \'97 comprehensive exam', n:compExams, mc:MC_RATES['92014'], cat:'clinic'\},\
    \{cpt:'99213', desc:'Established \'97 intermediate visit', n:intExams, mc:MC_RATES['99213'], cat:'clinic'\},\
    \{cpt:'99214', desc:'Established \'97 complex visit (glaucoma/HM)', n:glaucVisits, mc:MC_RATES['99214'], cat:'clinic'\},\
    \{cpt:'92133', desc:'OCT \'97 optic nerve', n:Math.round(octN*0.5), mc:MC_RATES['92133'], cat:'proc'\},\
    \{cpt:'92134', desc:'OCT \'97 retina', n:Math.round(octN*0.5), mc:MC_RATES['92134'], cat:'proc'\},\
    \{cpt:'92083', desc:'Visual fields', n:vfN, mc:MC_RATES['92083'], cat:'proc'\},\
    \{cpt:'68761', desc:'Punctal plugs', n:plugN, mc:MC_RATES['68761'], cat:'proc'\},\
    \{cpt:'65778', desc:'Prokera amniotic membrane', n:prokN, mc:MC_RATES['65778'], cat:'proc'\},\
    \{cpt:'92136', desc:'Biometry / IOL calc', n:bioN, mc:MC_RATES['92136'], cat:'proc'\},\
    \{cpt:'92250', desc:'Anterior segment photo', n:aspN, mc:MC_RATES['92250'], cat:'proc'\},\
    \{cpt:'92082', desc:'Fluorescein angiography', n:faN, mc:MC_RATES['92082'], cat:'proc'\},\
    \{cpt:'66984', desc:'Standard cataract (phaco)', n:stdN, mc:MC_RATES['66984'], cat:'sx'\},\
    \{cpt:'66982', desc:'Complex cataract', n:cplxN, mc:MC_RATES['66982'], cat:'sx'\},\
    \{cpt:'66991', desc:'Premium cataract (toric/EDOF base)', n:premN, mc:MC_RATES['66991'], cat:'sx'\},\
    \{cpt:'65820', desc:'MIGS \'97 goniotomy', n:gonioN, mc:MC_RATES['65820'], cat:'sx'\},\
    \{cpt:'66174', desc:'MIGS \'97 canaloplasty', n:canalN, mc:MC_RATES['66174'], cat:'sx'\},\
    \{cpt:'0449T', desc:'MIGS \'97 XEN gel stent', n:xenN, mc:MC_RATES['0449T'], cat:'sx'\},\
    \{cpt:'stent', desc:'MIGS \'97 stent-based (iStent/Hydrus add-on)', n:stentN, mc:350, cat:'sx'\},\
    \{cpt:'65855', desc:'SLT laser', n:slt2N, mc:MC_RATES['65855'], cat:'sx'\},\
    \{cpt:'66821', desc:'YAG capsulotomy', n:yagN, mc:MC_RATES['66821'], cat:'sx'\},\
    \{cpt:'66761', desc:'LPI', n:lpiN, mc:MC_RATES['66761'], cat:'sx'\},\
  ].filter(r=>r.n>0);\
\
  let clinicTotal=0, surgTotal=0;\
  const tbody = document.getElementById('cpt-body');\
  tbody.innerHTML = '';\
\
  let catMap = \{'clinic':'Clinic visits','proc':'In-clinic procedures','sx':'Surgery'\};\
  let lastCat = null;\
\
  rows.forEach(r => \{\
    if(r.cat !== lastCat) \{\
      lastCat = r.cat;\
      const hdr = document.createElement('tr');\
      hdr.innerHTML = `<td colspan="6" style="padding:8px 8px 4px;font-size:11px;font-weight:500;color:var(--color-text-secondary);text-transform:uppercase;letter-spacing:.05em;background:var(--color-background-tertiary)">$\{catMap[r.cat]\}</td>`;\
      tbody.appendChild(hdr);\
    \}\
    const bl = blended(r.mc);\
    const rev = r.n * bl;\
    if(r.cat==='clinic'||r.cat==='proc') clinicTotal+=rev; else surgTotal+=rev;\
    const tr = document.createElement('tr');\
    tr.innerHTML = `<td style="color:var(--color-text-secondary);font-family:var(--font-mono);font-size:11px">$\{r.cpt\}</td><td>$\{r.desc\}</td><td class="num">$\{fmt(r.mc)\}</td><td class="num">$\{r.n.toLocaleString()\}</td><td class="num">$\{fmt(bl)\}</td><td class="num" style="font-weight:500">$\{fmtk(rev)\}</td>`;\
    tbody.appendChild(tr);\
  \});\
\
  const totRow = document.createElement('tr');\
  totRow.className = 'total-row';\
  totRow.innerHTML = `<td colspan="5" style="padding:8px;font-weight:500">Insurance-adjusted total</td><td class="num" style="font-weight:500;padding:8px">$\{fmtk(clinicTotal+surgTotal)\}</td>`;\
  tbody.appendChild(totRow);\
\
  const cashRows = [\
    \{desc:'Femto laser', n:ni('femto-n'), price:sv('femto-price')\},\
    \{desc:'Vivity IOL (premium presbyopia)', n:ni('vivity-n'), price:sv('vivity-price')\},\
    \{desc:'PanOptix IOL (premium presbyopia)', n:ni('panoptix-n'), price:sv('panoptix-price')\},\
    \{desc:'EnVista / other presbyopia IOL', n:ni('envy-n'), price:sv('envy-price')\},\
    \{desc:'Toric IOL upgrade', n:ni('toric-n'), price:sv('toric-price')\},\
    \{desc:'Refractive/LASIK case', n:ni('lk-n'), price:sv('lk-price')\},\
  ].filter(r=>r.n>0&&r.price>0);\
\
  let cashTotal=0;\
  const cbody = document.getElementById('cash-body');\
  cbody.innerHTML='';\
  cashRows.forEach(r=>\{\
    const rev = r.n*r.price;\
    cashTotal+=rev;\
    const tr=document.createElement('tr');\
    tr.innerHTML=`<td>$\{r.desc\}</td><td class="num">$\{r.n\}</td><td class="num">$\{fmt(r.price)\}</td><td class="num" style="font-weight:500">$\{fmtk(rev)\}</td>`;\
    cbody.appendChild(tr);\
  \});\
  if(cashRows.length===0)\{\
    cbody.innerHTML='<tr><td colspan="4" style="color:var(--color-text-tertiary);padding:8px">No cash-pay services configured</td></tr>';\
  \} else \{\
    const tr=document.createElement('tr');\
    tr.className='total-row';\
    tr.innerHTML=`<td colspan="3" style="padding:8px;font-weight:500">Cash-pay total</td><td class="num" style="padding:8px;font-weight:500">$\{fmtk(cashTotal)\}</td>`;\
    cbody.appendChild(tr);\
  \}\
\
  const grandTotal = clinicTotal+surgTotal+cashTotal;\
  const annual = grandTotal*12;\
  document.getElementById('tot-col').textContent = fmtk(grandTotal);\
  document.getElementById('tot-sub').textContent = `$\{fmtk(clinicTotal+surgTotal)\} ins. + $\{fmtk(cashTotal)\} cash`;\
  document.getElementById('clinic-col').textContent = fmtk(clinicTotal);\
  document.getElementById('clinic-sub').textContent = `$\{clinicDaysPerMonth\} clinic days`;\
  document.getElementById('surg-col').textContent = fmtk(surgTotal);\
  document.getElementById('surg-sub').textContent = `$\{Math.round(totalSurgCases)\} surgical cases`;\
  document.getElementById('cash-col').textContent = fmtk(cashTotal);\
  document.getElementById('ann-col').textContent = fmtk(annual);\
\}\
\
upd();\
</script>\
}

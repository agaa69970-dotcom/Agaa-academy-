<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>AGAA ACADEMY - المستقبل</title>
<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:'Segoe UI',Tahoma,sans-serif}
body{background:#040807;color:#eafff3;overflow-x:hidden}
.top{position:sticky;top:0;z-index:10;display:flex;justify-content:space-between;align-items:center;padding:14px 16px;background:rgba(4,8,7,.9);backdrop-filter:blur(10px);border-bottom:1px solid #123}
.logo{font-weight:900;letter-spacing:2px;font-size:22px}
.logo span{color:#00ff88}
.badge{background:#00ff88;color:#000;padding:5px 10px;border-radius:20px;font-weight:800;font-size:12px;display:inline-block}
.hero{padding:22px 16px 10px;text-align:center}
.hero h1{font-size:32px;line-height:1.2}
.hero h1 b{color:#00ff88}
.hero p{opacity:.75;margin-top:8px;font-size:14px}
.tabs{display:flex;gap:8px;padding:12px 16px;overflow:auto}
.tab{white-space:nowrap;padding:10px 16px;border-radius:999px;border:1px solid #1e3a2d;background:#0a1510;color:#eafff3;cursor:pointer;font-weight:700}
.tab.active{background:#00ff88;color:#000;border-color:#00ff88}
.wrap{padding:0 14px 100px;max-width:900px;margin:auto}
.card{background:linear-gradient(180deg,#0d1f17,#07120d);border:1px solid #1c4a33;border-radius:20px;padding:16px;margin:14px 0;box-shadow:0 10px 40px rgba(0,0,0,.4)}
.profile{display:flex;gap:14px;align-items:center}
.avatar{width:72px;height:72px;border-radius:50%;background:radial-gradient(circle at 30% 30%,#00ff88,#00331d);display:grid;place-items:center;font-size:32px;border:2px solid #00ff88;flex-shrink:0}
.xpbar{height:14px;background:#12261c;border-radius:999px;overflow:hidden;margin-top:10px}
.xpfill{height:100%;background:linear-gradient(90deg,#00ff88,#00d4ff);transition:.5s}
.grid{display:grid;grid-template-columns:1fr 1fr;gap:10px;margin-top:12px}
.skill{background:#07150e;border:1px solid #1a3a2a;border-radius:14px;padding:12px}
.skill small{opacity:.7}
.dots{color:#00ff88;letter-spacing:2px}
.mission{display:flex;justify-content:space-between;align-items:center;background:#07150e;border:1px solid #1e3a2d;padding:12px;border-radius:14px;margin-top:10px;gap:10px}
.circle{width:54px;height:54px;border-radius:50%;border:4px solid #00ff88;display:grid;place-items:center;font-weight:900;flex-shrink:0}
.map{display:grid;grid-template-columns:1fr 1fr;gap:10px}

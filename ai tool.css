:root {
  --bg: #0f1220;
  --panel: #171a2b;
  --text: #e6e8f0;
  --muted: #a9aec5;
  --accent: #6c8cff;
  --bot: #21263f;
  --user: #243b55;
}

* { box-sizing: border-box; }
body {
  margin: 0; font-family: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, "Noto Sans", "Helvetica Neue", Arial;
  background: radial-gradient(900px 450px at 10% 10%, #131633, #0f1220);
  color: var(--text);
}
.app { max-width: 900px; margin: 0 auto; min-height: 100vh; display: grid; grid-template-rows: auto 1fr auto; gap: 12px; padding: 16px; }
header { background: var(--panel); border: 1px solid #2a3052; border-radius: 12px; padding: 16px; }
header h1 { margin: 0 0 4px; font-size: 20px; }
header p { margin: 0; color: var(--muted); font-size: 13px; }
main { background: var(--panel); border: 1px solid #2a3052; border-radius: 12px; padding: 12px; overflow: auto; }
#messages { display: flex; flex-direction: column; gap: 12px; }
.msg { display: flex; gap: 10px; align-items: flex-start; }
.msg .bubble {
  padding: 10px 12px; border-radius: 10px; max-width: 75%;
  line-height: 1.45; font-size: 14px; white-space: pre-wrap;
}
.msg.user .bubble { background: var(--user); border: 1px solid #385179; }
.msg.bot .bubble { background: var(--bot); border: 1px solid #343c5f; }
footer { background: var(--panel); border: 1px solid #2a3052; border-radius: 12px; padding: 12px; display: grid; gap: 8px; }
#chat-form { display: grid; grid-template-columns: 1fr auto auto; gap: 8px; }
#user-input, select, button, input[type="text"], input[type="password"] {
  background: #14172a; color: var(--text); border: 1px solid #2a3052; border-radius: 8px; padding: 10px;
}
button { background: var(--accent); border: none; color: white; cursor: pointer; }
.tip { display: grid; grid-template-columns: repeat(3, 1fr); gap: 8px; font-size: 12px; color: var(--muted); }
label { display: flex; align-items: center; gap: 6px; }
@media (max-width: 700px) {
  .tip { grid-template-columns: 1fr; }
  #chat-form { grid-template-columns: 1fr auto; }
}

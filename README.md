# nuvanta
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Safe Rant Board (Philippines)</title>
  <style>
    body { font-family: Arial, sans-serif; background: #f9fafc; padding: 20px; }
    main { max-width: 640px; margin: auto; background: white; padding: 24px; border-radius: 10px; box-shadow: 0 4px 12px rgba(0,0,0,0.08); }
    h1 { margin: 0 0 8px; color: #1f4f91; }
    p.help { margin: 0 0 16px; color: #334155;}
    textarea { width: 100%; height: 140px; margin-top: 8px; padding: 10px; border-radius: 8px; border: 1px solid #cbd5e1; }
    button { display: inline-block; margin-top: 12px; padding: 12px 16px; font-size: 15px; background: #2563eb; color: white; border: none; border-radius: 8px; cursor: pointer; }
    button:hover { filter: brightness(0.95); }
    .hotlines { margin-top: 28px; padding: 16px; background: #f1f5f9; border-left: 6px solid #2563eb; border-radius: 8px; }
    .hotlines h2 { margin-top: 0; color: #1f4f91; font-size: 18px; }
    .hotlines p { margin: 6px 0; }
    footer { margin-top: 16px; color: #475569; font-size: 12px; }
  </style>
</head>
<body>
  <main>
    <h1>Safe Rant Board</h1>
    <p class="help">Share anything on your mind. Your message goes privately to the counselor's inbox.</p>

    <form action="https://formsubmit.co/iyyasmgg@gmail.com" method="POST">
      <textarea id="message" name="message" placeholder="Write your rant..." maxlength="1000" required></textarea>
      <button type="submit">Send Rant</button>

      <!-- FormSubmit settings -->
      <input type="hidden" name="_captcha" value="false">
      <input type="hidden" name="_subject" value="New Rant Submission">
      <input type="hidden" name="_template" value="table">
      <input type="hidden" name="_autoresponse" value="Thanks for sharing your rant! It has been received.">
      <input type="hidden" name="_next" value="thank-you.html">

      <!-- Hotlines included in email -->
      <input type="hidden" name="DOH-NCMH Crisis Hotline" value="1553 (toll-free landline)">
      <input type="hidden" name="Globe/TM" value="0917-899-8727">
      <input type="hidden" name="Smart/Sun/TNT" value="0908-639-2672">
      <input type="hidden" name="Hopeline PH" value="(02) 8804-4673 / 0917-558-4673">
      <input type="hidden" name="In Touch Crisis Line" value="(02) 8893-7603">
    </form>

    <!-- Visible Hotlines -->
    <div class="hotlines">
      <h2>📞 Mental Health Hotlines (Philippines)</h2>
      <p><strong>DOH–NCMH Crisis Hotline:</strong> 1553 (toll-free landline)</p>
      <p><strong>Globe/TM:</strong> 0917-899-8727</p>
      <p><strong>Smart/Sun/TNT:</strong> 0908-639-2672</p>
      <p><strong>Hopeline PH:</strong> (02) 8804-4673 / 0917-558-4673</p>
      <p><strong>In Touch Crisis Line:</strong> (02) 8893-7603</p>
    </div>

    <footer>Note: Messages are private. If you are in immediate danger, call emergency services.</footer>
  </main>
</body>
</html>

<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>MVxCamera — Макеты экранов (HTML демонстрация)</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
  <style>
    /* Базовая тема и сетка. Единый стиль, единый масштаб, Material-like. */
    :root {
      --md-bg: #121212;
      --md-surface: #1E1E1E;
      --md-surface-2: #232323;
      --md-surface-3: #2A2A2A;
      --md-primary: #64B5F6;  /* Material Blue lighten */
      --md-primary-variant: #42A5F5;
      --md-secondary: #81C784; /* Material Green lighten */
      --md-error: #EF5350;
      --md-on-bg: #EAEAEA;
      --md-on-surface: #F5F5F5;
      --md-on-muted: #CFCFCF;
      --md-outline: #3A3A3A;
      --radius: 14px;
      --radius-sm: 10px;
      --shadow-1: 0 6px 16px rgba(0,0,0,0.25);
      --shadow-2: 0 10px 28px rgba(0,0,0,0.35);
      --focus: 0 0 0 3px rgba(100,181,246,0.45);
      --device-w: 392px; /* типичный Android phone width @scale */
      --device-h: 852px; /* типичный Android phone height @scale */
      --fab-size: 64px;
      --toolbar-h: 64px;
      --bottom-bar-h: 72px;
      --safe: 16px;
    }
    * { box-sizing: border-box; }
    body {
      margin: 0;
      padding: 24px;
      font-family: Inter, Roboto, system-ui, -apple-system, "Segoe UI", "Helvetica Neue", Arial, "Noto Sans", sans-serif;
      background: linear-gradient(180deg, #0D0D0D, #141414 30%, #191919 100%);
      color: var(--md-on-bg);
    }
    h1, h2 { font-weight: 700; margin: 8px 0 16px; }
    h3 { font-weight: 600; margin: 16px 0 12px; color: var(--md-on-muted); }
    .header {
      display: flex; align-items: center; gap: 12px; margin-bottom: 12px;
    }
    .legend {
      max-width: 1200px;
      margin-bottom: 24px;
      color: var(--md-on-muted);
      line-height: 1.55;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(calc(var(--device-w) + 32px), 1fr));
      gap: 24px;
      align-items: start;
    }
    .card {
      background: var(--md-surface);
      border: 1px solid var(--md-outline);
      border-radius: 16px;
      box-shadow: var(--shadow-1);
      padding: 16px;
    }
    .title-row {
      display: flex; justify-content: space-between; align-items: center; margin-bottom: 8px;
    }
    .badge {
      padding: 6px 10px;
      border-radius: 999px;
      font-size: 12px;
      background: var(--md-surface-3);
      color: var(--md-on-muted);
      border: 1px solid var(--md-outline);
    }
    .device {
      width: var(--device-w);
      height: var(--device-h);
      background: #000;
      border-radius: 28px;
      border: 1px solid #2E2E2E;
      box-shadow: var(--shadow-2);
      margin: 8px auto 0;
      position: relative;
      overflow: hidden;
    }
    /* Общие элементы Android: Top App Bar, Bottom Bar, FAB */
    .appbar {
      position: absolute; inset: 0 0 auto 0; height: var(--toolbar-h);
      background: rgba(30,30,30,0.85); backdrop-filter: blur(10px);
      border-bottom: 1px solid var(--md-outline);
      display: flex; align-items: center; gap: 10px; padding: 0 12px;
    }
    .appbar .title { font-weight: 600; letter-spacing: 0.2px; }
    .appbar .action {
      margin-left: auto; display: flex; align-items: center; gap: 8px;
    }
    .appbar button.icon {
      width: 40px; height: 40px; border-radius: 12px; border: 1px solid var(--md-outline);
      background: var(--md-surface-2); color: var(--md-on-surface);
    }
    .content {
      position: absolute; inset: var(--toolbar-h) 0 var(--bottom-bar-h) 0;
      overflow: hidden;
      background: #000;
    }
    .bottom-bar {
      position: absolute; inset: auto 0 0 0; height: var(--bottom-bar-h);
      background: rgba(30,30,30,0.9); backdrop-filter: blur(10px);
      border-top: 1px solid var(--md-outline);
      display: grid; grid-template-columns: repeat(5, 1fr);
      gap: 6px; padding: 8px;
    }
    .bottom-item {
      display: grid; place-items: center; color: var(--md-on-muted);
      font-size: 12px; gap: 6px;
    }
    .bottom-item .ico {
      width: 28px; height: 28px; border-radius: 10px;
      background: var(--md-surface-2); border: 1px solid var(--md-outline);
    }
    .bottom-item.active .ico { background: var(--md-primary-variant); border-color: transparent; }
    .fab {
      position: absolute; right: 16px; bottom: calc(var(--bottom-bar-h) + 16px);
      width: var(--fab-size); height: var(--fab-size); border-radius: 22px;
      display: grid; place-items: center; background: var(--md-primary);
      color: #021722; font-weight: 700; box-shadow: var(--shadow-2);
      border: 2px solid rgba(255,255,255,0.15);
    }
    .fab:focus-visible { outline: none; box-shadow: var(--focus); }

    /* Видоискатель и оверлеи */
    .viewfinder {
      position: absolute; inset: 0; background:
        radial-gradient(1200px 500px at 30% 30%, rgba(30,30,30,0.35), transparent 40%),
        linear-gradient(180deg, #0A0A0A 0%, #111 33%, #000 100%);
      display: grid; place-items: center;
    }
    .vf-image {
      width: 94%; height: 86%; border-radius: 20px; overflow: hidden;
      background: url('https://images.unsplash.com/photo-1483728642387-6c3bdd6c93e5?q=80&w=1960&auto=format&fit=crop') center/cover no-repeat;
      filter: saturate(1.15) contrast(1.05) brightness(0.95);
      border: 1px solid rgba(255,255,255,0.065);
      box-shadow: 0 80px 120px rgba(0,0,0,0.5) inset;
      position: relative;
    }
    .overlay-grid {
      position: absolute; inset: 0; pointer-events: none;
      background-image:
        linear-gradient(rgba(255,255,255,0.06) 1px, transparent 1px),
        linear-gradient(90deg, rgba(255,255,255,0.06) 1px, transparent 1px);
      background-size: calc(100%/3) calc(100%/3);
      border-radius: 20px;
    }
    .overlay-hist {
      position: absolute; left: 14px; bottom: 14px; width: 160px; height: 80px;
      background: linear-gradient(180deg, rgba(0,0,0,0.65), rgba(0,0,0,0.3));
      border-radius: 12px; border: 1px solid rgba(255,255,255,0.08);
      overflow: hidden;
    }
    .overlay-hist::before {
      content: ""; position: absolute; inset: 0;
      background: url('https://dummyimage.com/160x80/000/fff&text=hist') center/cover no-repeat;
      opacity: 0.35;
    }
    .overlay-zebra {
      position: absolute; inset: 0; pointer-events: none;
      background-image: repeating-linear-gradient(
        45deg, rgba(255,0,0,0.2) 0 6px, transparent 6px 12px
      );
      mix-blend-mode: screen; opacity: 0.0; /* выключено, демонстрация в экране ассистентов */
      border-radius: 20px;
    }
    .param-dock {
      position: absolute; right: 10px; top: 14px; width: 72px;
      display: flex; flex-direction: column; gap: 8px;
    }
    .chip {
      width: 100%; border-radius: 12px; padding: 10px 8px;
      background: rgba(24,24,24,0.75); border: 1px solid var(--md-outline);
      color: var(--md-on-surface); font-size: 12px; display: grid; gap: 4px;
    }
    .chip .label { font-size: 10px; color: var(--md-on-muted); }
    .chip .value { font-weight: 600; }
    .knob {
      height: 44px; border-radius: 12px; background: var(--md-surface-2);
      border: 1px solid var(--md-outline); display: grid; place-items: center; color: var(--md-on-muted);
    }

    /* Панель параметров снизу (ISO, Shutter, WB, Focus, EV, Format) */
    .param-bar {
      position: absolute; left: 0; right: 0; bottom: calc(var(--bottom-bar-h) + 8px);
      display: grid; grid-template-columns: repeat(6, 1fr); gap: 8px; padding: 0 12px;
    }
    .param-item {
      background: rgba(20,20,20,0.9); border: 1px solid var(--md-outline);
      border-radius: 12px; padding: 8px; display: grid; gap: 4px;
      color: var(--md-on-surface);
    }
    .param-item .key { font-size: 10px; color: var(--md-on-muted); }
    .param-item .val { font-size: 12px; font-weight: 600; }
    .param-slider {
      height: 6px; border-radius: 8px; background: #333; position: relative; overflow: hidden;
    }
    .param-slider .fill {
      position: absolute; left: 0; top: 0; bottom: 0; width: 60%;
      background: linear-gradient(90deg, var(--md-primary), var(--md-primary-variant));
    }

    /* Листы / меню, модальные, и т.д. */
    .sheet {
      position: absolute; inset: auto 0 0 0; height: 58%;
      background: var(--md-surface-2); border-top-left-radius: 18px; border-top-right-radius: 18px;
      border-top: 1px solid var(--md-outline); box-shadow: 0 -16px 36px rgba(0,0,0,0.45);
      display: none; /* включаем на соответствующих экранах */
    }
    .sheet.visible { display: block; }
    .sheet .drag {
      width: 42px; height: 5px; border-radius: 4px; background: #4A4A4A; margin: 10px auto;
    }
    .sheet .inner { padding: 10px; height: calc(100% - 24px); overflow: auto; }
    .list {
      display: grid; gap: 10px;
    }
    .list-item {
      display: grid; grid-template-columns: auto 1fr auto; gap: 12px; align-items: center;
      background: var(--md-surface-3); border: 1px solid var(--md-outline);
      padding: 12px; border-radius: 12px;
    }
    .list-item .ico {
      width: 36px; height: 36px; border-radius: 10px; background: var(--md-primary-variant);
      display: grid; place-items: center; color: #032038; font-weight: 700;
    }
    .list-item .title { font-weight: 600; }
    .list-item .sub { font-size: 12px; color: var(--md-on-muted); }
    .list-item .go {
      width: 36px; height: 36px; border-radius: 10px; background: var(--md-surface-2);
      border: 1px solid var(--md-outline);
    }

    /* Формы и поля */
    .field {
      display: grid; gap: 6px; margin-bottom: 12px;
    }
    .field label { font-size: 12px; color: var(--md-on-muted); }
    .field input, .field select, .field textarea {
      background: var(--md-surface-3); border: 1px solid var(--md-outline); color: var(--md-on-surface);
      border-radius: 12px; padding: 10px 12px; font-size: 14px;
    }
    .row { display: flex; gap: 10px; }
    .btn {
      background: var(--md-primary); color: #06111C; border: none; border-radius: 12px;
      padding: 10px 14px; font-weight: 700; box-shadow: var(--shadow-1); cursor: pointer;
    }
    .btn.secondary { background: var(--md-secondary); color: #03160C; }
    .btn.ghost {
      background: transparent; color: var(--md-on-surface);
      border: 1px solid var(--md-outline);
    }

    /* Статусные компоненты */
    .status {
      background: rgba(22,22,22,0.85); border: 1px solid var(--md-outline);
      color: var(--md-on-muted); border-radius: 12px; padding: 8px 10px; font-size: 12px;
    }
    .status.ok { color: #A8E6A3; }
    .status.warn { color: #F1C27D; }
    .status.err { color: #F28B82; }

    /* Навигационная подсказка */
    .nav-note {
      font-size: 12px; color: var(--md-on-muted); margin-top: 8px;
    }
    a.link { color: var(--md-primary); text-decoration: none; }

    /* Для единых отступов контента на экранах, чтобы ничего не "ехало" */
    .padded { padding: var(--safe); }
  </style>
</head>
<body>
  <div class="header">
    <h1>MVxCamera — Комплект макетов экранных форм</h1>
    <span class="badge">Материалы: Nielsen Heuristics · Material Design · Единый стиль</span>
  </div>
  <div class="legend">
    Ниже представлены HTML-макеты ключевых экранов Android-приложения «МVx-камера», соответствующие заявленным сценариям использования:
    ручной контроль параметров (ISO, выдержка, диафрагма*, фокус, баланс белого, экспозиция), работа с пресетами, интеграция с системами смартфона
    (сенсоры, публикация/поделиться), производительность, адаптивность, облачная синхронизация пресетов, интерактивная справка/FAQ, разрешения и настройки.
    Все экраны выдержаны в едином стиле, едином масштабе и учитывают эвристики Нильсена: видимость состояния системы, соответствие реальному миру,
    контроль и свобода, консистентность, предотвращение ошибок, распознавание вместо вспоминания, гибкость и эффективность, минимализм, помощь и документация.
    Примечание: диафрагма доступна только при аппаратной поддержке — элемент отображается, но может быть неактивен на неподдерживаемых устройствах.
  </div>

  <div class="grid">
    <!-- 1. Экран камеры (основной, видоискатель, ручной контроль) -->
    <div class="card">
      <div class="title-row">
        <h2>1. Камера (Видоискатель)</h2>
        <span class="badge">Ручной режим · ISO · Shutter · WB · Focus · EV · Format</span>
      </div>
      <div class="device" role="region" aria-label="Экран — Камера">
        <div class="appbar">
          <button class="icon" aria-label="Меню">&#9776;</button>
          <div class="title">MVxCamera</div>
          <div class="action">
            <button class="icon" aria-label="Гистограмма">H</button>
            <button class="icon" aria-label="Сетка">#</button>
            <button class="icon" aria-label="Ассистенты">A</button>
          </div>
        </div>

        <div class="content">
          <div class="viewfinder">
            <div class="vf-image">
              <div class="overlay-grid" aria-hidden="true"></div>
              <div class="overlay-zebra" aria-hidden="true"></div>
              <div class="overlay-hist" aria-label="Гистограмма"></div>
            </div>
          </div>

          <!-- Панель параметров -->
          <div class="param-bar padded" aria-label="Панель ручных параметров">
            <div class="param-item" title="ISO">
              <div class="key">ISO</div>
              <div class="val">200</div>
              <div class="param-slider"><div class="fill" style="width:40%"></div></div>
            </div>
            <div class="param-item" title="Выдержка">
              <div class="key">Shutter</div>
              <div class="val">1/125</div>
              <div class="param-slider"><div class="fill" style="width:55%"></div></div>
            </div>
            <div class="param-item" title="Баланс белого">
              <div class="key">WB</div>
              <div class="val">5500K</div>
              <div class="param-slider"><div class="fill" style="width:60%"></div></div>
            </div>
            <div class="param-item" title="Фокус">
              <div class="key">Focus</div>
              <div class="val">MF 0.75</div>
              <div class="param-slider"><div class="fill" style="width:75%"></div></div>
            </div>
            <div class="param-item" title="Экспокоррекция">
              <div class="key">EV</div>
              <div class="val">+0.3</div>
              <div class="param-slider"><div class="fill" style="width:65%"></div></div>
            </div>
            <div class="param-item" title="Формат">
              <div class="key">Format</div>
              <div class="val">RAW + JPEG</div>
              <div class="param-slider"><div class="fill" style="width:80%"></div></div>
            </div>
          </div>

          <!-- Панель быстрых чипов справа -->
          <div class="param-dock" aria-label="Быстрые параметры">
            <div class="chip">
              <div class="label">Aperture</div>
              <div class="value">f/1.8</div>
              <div class="knob">HW</div>
            </div>
            <div class="chip">
              <div class="label">Metering</div>
              <div class="value">Center</div>
              <div class="knob">MTR</div>
            </div>
            <div class="chip">
              <div class="label">Stabilizer</div>
              <div class="value">ON</div>
              <div class="knob">OIS</div>
            </div>
          </div>

          <!-- FAB — спуск затвора -->
          <button class="fab" aria-label="Сделать снимок">●</button>
        </div>

        <div class="bottom-bar" role="tablist" aria-label="Навигация">
          <div class="bottom-item active" role="tab" aria-selected="true">
            <div class="ico">📷</div><div>Камера</div>
          </div>
          <div class="bottom-item" role="tab"><div class="ico">🎛️</div><div>Пресеты</div></div>
          <div class="bottom-item" role="tab"><div class="ico">🧭</div><div>Ассистенты</div></div>
          <div class="bottom-item" role="tab"><div class="ico">☁️</div><div>Облако</div></div>
          <div class="bottom-item" role="tab"><div class="ico">⚙️</div><div>Настройки</div></div>
        </div>
      </div>
      <div class="nav-note">Основной сценарий: полный ручной контроль параметров, видимость состояния (оверлеи, гистограмма, сетка), мгновенное применение настроек.</div>
    </div>

    <!-- 2. Пресеты: список -->
    <div class="card">
      <div class="title-row">
        <h2>2. Пресеты — Список</h2>
        <span class="badge">Создание · Хранение · Быстрое переключение</span>
      </div>
      <div class="device" role="region" aria-label="Экран — Пресеты список">
        <div class="appbar">
          <button class="icon" aria-label="Назад">←</button>
          <div class="title">Пресеты</div>
          <div class="action">
            <button class="icon" aria-label="Добавить пресет">＋</button>
            <button class="icon" aria-label="Фильтр">⧉</button>
          </div>
        </div>
        <div class="content padded" style="background: var(--md-surface-2);">
          <div class="status ok">Синхронизация: включена. 12 пресетов, последний импорт — 2 ч назад.</div>
          <div class="list" style="margin-top: 10px">
            <div class="list-item">
              <div class="ico">P</div>
              <div>
                <div class="title">Street Quick</div>
                <div class="sub">ISO 400 · 1/250 · WB 5200K · MF 0.6 · EV +0.3 · RAW+JPEG</div>
              </div>
              <button class="go" aria-label="Применить пресет">→</button>
            </div>
            <div class="list-item">
              <div class="ico">P</div>
              <div>
                <div class="title">Portrait Soft</div>
                <div class="sub">ISO 100 · 1/125 · WB 5000K · AF face · EV +0.0 · JPEG</div>
              </div>
              <button class="go" aria-label="Применить пресет">→</button>
            </div>
            <div class="list-item">
              <div class="ico">P</div>
              <div>
                <div class="title">Landscape Long</div>
                <div class="sub">ISO 64 · 2s · WB 5600K · MF 0.9 · EV −0.3 · RAW</div>
              </div>
              <button class="go" aria-label="Применить пресет">→</button>
            </div>
            <div class="list-item">
              <div class="ico">P</div>
              <div>
                <div class="title">Night Low-Noise</div>
                <div class="sub">ISO 800 · 1/30 · WB Auto · AF · EV +0.7 · RAW</div>
              </div>
              <button class="go" aria-label="Применить пресет">→</button>
            </div>
          </div>
        </div>
        <div class="bottom-bar">
          <div class="bottom-item"><div class="ico">📷</div><div>Камера</div></div>
          <div class="bottom-item active"><div class="ico">🎛️</div><div>Пресеты</div></div>
          <div class="bottom-item"><div class="ico">🧭</div><div>Ассистенты</div></div>
          <div class="bottom-item"><div class="ico">☁️</div><div>Облако</div></div>
          <div class="bottom-item"><div class="ico">⚙️</div><div>Настройки</div></div>
        </div>
      </div>
      <div class="nav-note">Сценарии: хранение пресетов, быстрый выбор, консистентная карточка, распознавание вместо вспоминания.</div>
    </div>

    <!-- 3. Пресеты: редактор -->
    <div class="card">
      <div class="title-row">
        <h2>3. Пресеты — Редактор</h2>
        <span class="badge">Создать · Изменить · Сохранить · Поделиться</span>
      </div>
      <div class="device" role="region" aria-label="Экран — Редактор пресета">
        <div class="appbar">
          <button class="icon" aria-label="Назад">←</button>
          <div class="title">Редактор пресета</div>
          <div class="action">
            <button class="icon" aria-label="Сохранить">💾</button>
            <button class="icon" aria-label="Поделиться">⤴</button>
          </div>
        </div>
        <div class="content padded" style="background: var(--md-surface-2); overflow:auto;">
          <div class="field">
            <label>Название пресета</label>
            <input type="text" value="Portrait Soft">
          </div>
          <div class="row">
            <div class="field" style="flex:1">
              <label>ISO</label>
              <input type="number" value="100" min="50" max="6400">
            </div>
            <div class="field" style="flex:1">
              <label>Выдержка</label>
              <select>
                <option selected>1/125</option>
                <option>1/250</option>
                <option>1/60</option>
                <option>1/30</option>
              </select>
            </div>
          </div>
          <div class="row">
            <div class="field" style="flex:1">
              <label>Баланс белого (K)</label>
              <input type="number" value="5000" min="2000" max="9000">
            </div>
            <div class="field" style="flex:1">
              <label>Фокус</label>
              <select>
                <option>AF Face</option>
                <option selected>MF 0.75</option>
                <option>AF Continuous</option>
              </select>
            </div>
          </div>
          <div class="row">
            <div class="field" style="flex:1">
              <label>Экспокоррекция (EV)</label>
              <input type="text" value="+0.0">
            </div>
            <div class="field" style="flex:1">
              <label>Формат</label>
              <select>
                <option>JPEG</option>
                <option selected>RAW + JPEG</option>
                <option>HEIF</option>
              </select>
            </div>
          </div>
          <div class="status warn">Диафрагма (Aperture) доступна только при HW-поддержке. Текущее устройство: поддерживается f/1.8.</div>
          <div class="row" style="margin-top:8px">
            <button class="btn">Сохранить</button>
            <button class="btn secondary">Применить</button>
            <button class="btn ghost">Отмена</button>
          </div>
        </div>
        <div class="bottom-bar">
          <div class="bottom-item"><div class="ico">📷</div><div>Камера</div></div>
          <div class="bottom-item active"><div class="ico">🎛️</div><div>Пресеты</div></div>
          <div class="bottom-item"><div class="ico">🧭</div><div>Ассистенты</div></div>
          <div class="bottom-item"><div class="ico">☁️</div><div>Облако</div></div>
          <div class="bottom-item"><div class="ico">⚙️</div><div>Настройки</div></div>
        </div>
      </div>
      <div class="nav-note">Сценарии: создание/редактирование, сохранение, применение, публикация пресета.</div>
    </div>

    <!-- 4. Ассистенты (сенсоры, гистограмма, зебра, фокус-пикинг) -->
    <div class="card">
      <div class="title-row">
        <h2>4. Ассистенты съемки</h2>
        <span class="badge">Сенсоры · Гистограмма · Сетка · Зебра · Фокус-пикинг</span>
      </div>
      <div class="device" role="region" aria-label="Экран — Ассистенты">
        <div class="appbar">
          <button class="icon" aria-label="Назад">←</button>
          <div class="title">Ассистенты</div>
          <div class="action"><button class="icon" aria-label="Справка">?</button></div>
        </div>
        <div class="content" style="background:#000;">
          <div class="viewfinder">
            <div class="vf-image">
              <div class="overlay-grid"></div>
              <div class="overlay-zebra" style="opacity:0.4;"></div>
              <div class="overlay-hist"></div>
              <!-- Имитируем фокус-пикинг (зелёные контуры) -->
              <div style="position:absolute; inset:0; pointer-events:none;">
                <svg width="100%" height="100%">
                  <rect x="18%" y="22%" width="24%" height="18%" fill="none" stroke="#81C784" stroke-width="2" opacity="0.6"/>
                  <rect x="58%" y="46%" width="18%" height="14%" fill="none" stroke="#81C784" stroke-width="2" opacity="0.6"/>
                </svg>
              </div>
            </div>
          </div>
          <div class="sheet visible">
            <div class="drag"></div>
            <div class="inner">
              <div class="list">
                <div class="list-item">
                  <div class="ico">S</div>
                  <div>
                    <div class="title">Сенсоры</div>
                    <div class="sub">Освещённость: 320 lx · Угол: 12° вправо</div>
                  </div>
                  <button class="go" aria-label="Настроить">⚙️</button>
                </div>
                <div class="list-item">
                  <div class="ico">G</div>
                  <div>
                    <div class="title">Гистограмма</div>
                    <div class="sub">Показать поверх видоискателя</div>
                  </div>
                  <button class="go" aria-label="Вкл/Выкл">I/O</button>
                </div>
                <div class="list-item">
                  <div class="ico">#</div>
                  <div>
                    <div class="title">Сетка</div>
                    <div class="sub">Правило третей</div>
                  </div>
                  <button class="go" aria-label="Выбор типа">⋯</button>
                </div>
                <div class="list-item">
                  <div class="ico">Z</div>
                  <div>
                    <div class="title">Зебра</div>
                    <div class="sub">Порог: 95% яркости</div>
                  </div>
                  <button class="go" aria-label="Вкл/Выкл">I/O</button>
                </div>
                <div class="list-item">
                  <div class="ico">F</div>
                  <div>
                    <div class="title">Фокус-пикинг</div>
                    <div class="sub">Цвет контура: зелёный · Сила: средняя</div>
                  </div>
                  <button class="go" aria-label="Настроить">⋯</button>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="bottom-bar">
          <div class="bottom-item"><div class="ico">📷</div><div>Камера</div></div>
          <div class="bottom-item"><div class="ico">🎛️</div><div>Пресеты</div></div>
          <div class="bottom-item active"><div class="ico">🧭</div><div>Ассистенты</div></div>
          <div class="bottom-item"><div class="ico">☁️</div><div>Облако</div></div>
          <div class="bottom-item"><div class="ico">⚙️</div><div>Настройки</div></div>
        </div>
      </div>
      <div class="nav-note">Сценарии: включение/настройка ассистентов, быстрая адаптация под сцену, видимость состояния.</div>
    </div>

    <!-- 5. Облако: вход/синхронизация пресетов -->
    <div class="card">
      <div class="title-row">
        <h2>5. Облачная синхронизация</h2>
        <span class="badge">Авторизация · Синхронизация · Конфликты</span>
      </div>
      <div class="device" role="region" aria-label="Экран — Облако">
        <div class="appbar">
          <button class="icon" aria-label="Назад">←</button>
          <div class="title">Облако пресетов</div>
          <div class="action"><button class="icon" aria-label="Справка">?</button></div>
        </div>
        <div class="content padded" style="background: var(--md-surface-2);">
          <div class="status">Статус: Не выполнен вход</div>
          <div class="field" style="margin-top:10px">
            <label>E-mail</label>
            <input type="email" placeholder="name@example.com">
          </div>
          <div class="field">
            <label>Пароль</label>
            <input type="password" placeholder="••••••••">
          </div>
          <div class="row">
            <button class="btn">Войти</button>
            <button class="btn ghost">Зарегистрироваться</button>
          </div>

          <h3 style="margin-top:16px;">Состояние синхронизации</h3>
          <div class="status warn">После входа: 12 локальных пресетов, 14 на сервере. Требуется разрешить конфликт.</div>
          <div class="row" style="margin-top:8px">
            <button class="btn secondary">Слить и объединить</button>
            <button class="btn ghost">Заменить локальные</button>
          </div>
        </div>
        <div class="bottom-bar">
          <div class="bottom-item"><div class="ico">📷</div><div>Камера</div></div>
          <div class="bottom-item"><div class="ico">🎛️</div><div>Пресеты</div></div>
          <div class="bottom-item"><div class="ico">🧭</div><div>Ассистенты</div></div>
          <div class="bottom-item active"><div class="ico">☁️</div><div>Облако</div></div>
          <div class="bottom-item"><div class="ico">⚙️</div><div>Настройки</div></div>
        </div>
      </div>
      <div class="nav-note">Сценарии: безопасная авторизация, синхронизация между устройствами, разрешение конфликтов.</div>
    </div>

    <!-- 6. Поделиться снимком / пресетом -->
    <div class="card">
      <div class="title-row">
        <h2>6. Поделиться</h2>
        <span class="badge">Публикация результатов · Метаданные настроек</span>
      </div>
      <div class="device" role="region" aria-label="Экран — Поделиться">
        <div class="appbar">
          <button class="icon" aria-label="Назад">←</button>
          <div class="title">Поделиться</div>
          <div class="action"><button class="icon" aria-label="История">🗂️</button></div>
        </div>
        <div class="content padded" style="background: var(--md-surface-2);">
          <div class="field">
            <label>Выберите тип</label>
            <select>
              <option selected>Снимок</option>
              <option>Пресет</option>
            </select>
          </div>
          <div class="field">
            <label>Платформа</label>
            <select>
              <option>Instagram</option>
              <option>Telegram</option>
              <option selected>Системное «Поделиться»</option>
            </select>
          </div>
          <div class="field">
            <label>Описание</label>
            <textarea rows="3" placeholder="Короткое описание...">ISO 200, 1/125, WB 5500K, MF 0.75, EV +0.3, RAW+JPEG</textarea>
          </div>
          <div class="row">
            <button class="btn">Отправить</button>
            <button class="btn ghost">Отмена</button>
          </div>
        </div>
        <div class="bottom-bar">
          <div class="bottom-item"><div class="ico">📷</div><div>Камера</div></div>
          <div class="bottom-item"><div class="ico">🎛️</div><div>Пресеты</div></div>
          <div class="bottom-item"><div class="ico">🧭</div><div>Ассистенты</div></div>
          <div class="bottom-item"><div class="ico">☁️</div><div>Облако</div></div>
          <div class="bottom-item active"><div class="ico">⚙️</div><div>Настройки</div></div>
        </div>
      </div>
      <div class="nav-note">Сценарии: публикация снимка/пресета, автогенерация метаданных параметров для подписи.</div>
    </div>

    <!-- 7. Настройки -->
    <div class="card">
      <div class="title-row">
        <h2>7. Настройки</h2>
        <span class="badge">Производительность · Форматы · Интерфейс</span>
      </div>
      <div class="device" role="region" aria-label="Экран — Настройки">
        <div class="appbar">
          <button class="icon" aria-label="Назад">←</button>
          <div class="title">Настройки</div>
          <div class="action"><button class="icon" aria-label="О приложении">ⓘ</button></div>
        </div>
        <div class="content padded" style="background: var(--md-surface-2); overflow:auto;">
          <div class="list">
            <div class="list-item">
              <div class="ico">⚡</div>
              <div>
                <div class="title">Производительность</div>
                <div class="sub">60 FPS UI · Быстрый запуск · Низкое энергопотребление</div>
              </div>
              <button class="go" aria-label="Изменить">⋯</button>
            </div>
            <div class="list-item">
              <div class="ico">🗂️</div>
              <div>
                <div class="title">Форматы сохранения</div>
                <div class="sub">JPEG · RAW (DNG) · HEIF</div>
              </div>
              <button class="go" aria-label="Выбор">⋯</button>
            </div>
            <div class="list-item">
              <div class="ico">🎚️</div>
              <div>
                <div class="title">Панель параметров</div>
                <div class="sub">Порядок и видимые элементы</div>
              </div>
              <button class="go" aria-label="Настроить">⋯</button>
            </div>
            <div class="list-item">
              <div class="ico">🔒</div>
              <div>
                <div class="title">Безопасность</div>
                <div class="sub">Приватность пресетов · Облачная авторизация</div>
              </div>
              <button class="go" aria-label="Изменить">⋯</button>
            </div>
            <div class="list-item">
              <div class="ico">🖼️</div>
              <div>
                <div class="title">Оверлеи</div>
                <div class="sub">Гистограмма · Зебра · Сетка · Пикинг</div>
              </div>
              <button class="go" aria-label="Выбор">⋯</button>
            </div>
          </div>
          <div class="status" style="margin-top:10px;">Минимальные требования: Android 7.0+, Camera2 API, RAM ≥ 6 GB, Storage ≥ 64 GB.</div>
        </div>
        <div class="bottom-bar">
          <div class="bottom-item"><div class="ico">📷</div><div>Камера</div></div>
          <div class="bottom-item"><div class="ico">🎛️</div><div>Пресеты</div></div>
          <div class="bottom-item"><div class="ico">🧭</div><div>Ассистенты</div></div>
          <div class="bottom-item"><div class="ico">☁️</div><div>Облако</div></div>
          <div class="bottom-item active"><div class="ico">⚙️</div><div>Настройки</div></div>
        </div>
      </div>
      <div class="nav-note">Сценарии: тонкая настройка интерфейса и поведения, соответствие системным ограничениям и требованиям.</div>
    </div>

    <!-- 8. Разрешения (Camera/Storage/Sensors) -->
    <div class="card">
      <div class="title-row">
        <h2>8. Разрешения</h2>
        <span class="badge">Camera · Storage · Sensors</span>
      </div>
      <div class="device" role="region" aria-label="Экран — Разрешения">
        <div class="appbar">
          <button class="icon" aria-label="Назад">←</button>
          <div class="title">Разрешения</div>
          <div class="action"><button class="icon" aria-label="Справка">?</button></div>
        </div>
        <div class="content padded" style="background: var(--md-surface-2);">
          <div class="list">
            <div class="list-item">
              <div class="ico">📷</div>
              <div>
                <div class="title">Доступ к камере</div>
                <div class="sub">Необходимо для съёмки и управления параметрами (Camera2 API)</div>
              </div>
              <button class="go" aria-label="Разрешить">✔</button>
            </div>
            <div class="list-item">
              <div class="ico">💾</div>
              <div>
                <div class="title">Доступ к хранилищу</div>
                <div class="sub">Сохранение снимков и пресетов (RAW/JPEG/HEIF)</div>
              </div>
              <button class="go" aria-label="Разрешить">✔</button>
            </div>
            <div class="list-item">
              <div class="ico">🧭</div>
              <div>
                <div class="title">Датчики</div>
                <div class="sub">Освещённость и положение для ассистентов</div>
              </div>
              <button class="go" aria-label="Разрешить">✔</button>
            </div>
          </div>
          <div class="status err" style="margin-top:10px;">Без доступа к камере приложение не сможет работать в ручном режиме.</div>
        </div>
        <div class="bottom-bar">
          <div class="bottom-item"><div class="ico">📷</div><div>Камера</div></div>
          <div class="bottom-item"><div class="ico">🎛️</div><div>Пресеты</div></div>
          <div class="bottom-item"><div class="ico">🧭</div><div>Ассистенты</div></div>
          <div class="bottom-item"><div class="ico">☁️</div><div>Облако</div></div>
          <div class="bottom-item active"><div class="ico">⚙️</div><div>Настройки</div></div>
        </div>
      </div>
      <div class="nav-note">Сценарии: просьба о разрешениях, объяснение причин, предотвращение ошибок.</div>
    </div>

    <!-- 9. Интерактивная справка (FAQ) -->
    <div class="card">
      <div class="title-row">
        <h2>9. Справка / FAQ</h2>
        <span class="badge">Поиск · Темы · Подсказки</span>
      </div>
      <div class="device" role="region" aria-label="Экран — Справка">
        <div class="appbar">
          <button class="icon" aria-label="Назад">←</button>
          <div class="title">Справка</div>
          <div class="action"><button class="icon" aria-label="Поиск">🔎</button></div>
        </div>
        <div class="content padded" style="background: var(--md-surface-2); overflow:auto;">
          <div class="field">
            <label>Поиск по ключевым словам</label>
            <input type="text" placeholder="Например: RAW, выдержка, пресеты">
          </div>
          <div class="list">
            <div class="list-item">
              <div class="ico">?</div>
              <div>
                <div class="title">Как настроить выдержку и ISO</div>
                <div class="sub">Справочник по панели параметров снизу</div>
              </div>
              <button class="go" aria-label="Читать">→</button>
            </div>
            <div class="list-item">
              <div class="ico">?</div>
              <div>
                <div class="title">Что такое RAW и когда его использовать</div>
                <div class="sub">Преимущества и ограничения</div>
              </div>
              <button class="go" aria-label="Читать">→</button>
            </div>
            <div class="list-item">
              <div class="ico">?</div>
              <div>
                <div class="title">Фокус-пикинг и зебра</div>
                <div class="sub">Визуальные ассистенты для точной съёмки</div>
              </div>
              <button class="go" aria-label="Читать">→</button>
            </div>
          </div>
        </div>
        <div class="bottom-bar">
          <div class="bottom-item"><div class="ico">📷</div><div>Камера</div></div>
          <div class="bottom-item"><div class="ico">🎛️</div><div>Пресеты</div></div>
          <div class="bottom-item"><div class="ico">🧭</div><div>Ассистенты</div></div>
          <div class="bottom-item"><div class="ico">☁️</div><div>Облако</div></div>
          <div class="bottom-item active"><div class="ico">⚙️</div><div>Настройки</div></div>
        </div>
      </div>
      <div class="nav-note">Сценарии: помощь и документация, поисковая выдача, минимизация когнитивной нагрузки.</div>
    </div>

    <!-- 10. О приложении / Маркировка -->
    <div class="card">
      <div class="title-row">
        <h2>10. О приложении</h2>
        <span class="badge">Маркировка · Лицензия · Версия</span>
      </div>
      <div class="device" role="region" aria-label="Экран — О приложении">
        <div class="appbar">
          <button class="icon" aria-label="Назад">←</button>
          <div class="title">О приложении</div>
          <div class="action"><button class="icon" aria-label="Правовая информация">§</button></div>
        </div>
        <div class="content padded" style="background: var(--md-surface-2); overflow:auto;">
          <div class="status">MVxCamera · Версия 1.0</div>
          <div class="list" style="margin-top:10px">
            <div class="list-item">
              <div class="ico">ⓘ</div>
              <div>
                <div class="title">Лицензионное соглашение</div>
                <div class="sub">Google Play · RuStore · Авторские права</div>
              </div>
              <button class="go" aria-label="Открыть">→</button>
            </div>
            <div class="list-item">
              <div class="ico">🏛️</div>
              <div>
                <div class="title">МИНОБРНАУКИ России · СПбГЭТУ «ЛЭТИ»</div>
                <div class="sub">Кафедра МО ЭВМ · Отчет по ПЧМИ</div>
              </div>
              <button class="go" aria-label="Подробнее">→</button>
            </div>
            <div class="list-item">
              <div class="ico">🔗</div>
              <div>
                <div class="title">Открытый API</div>
                <div class="sub">Интеграции с другими приложениями и устройствами</div>
              </div>
              <button class="go" aria-label="Документация">→</button>
            </div>
          </div>
        </div>
        <div class="bottom-bar">
          <div class="bottom-item"><div class="ico">📷</div><div>Камера</div></div>
          <div class="bottom-item"><div class="ico">🎛️</div><div>Пресеты</div></div>
          <div class="bottom-item"><div class="ico">🧭</div><div>Ассистенты</div></div>
          <div class="bottom-item"><div class="ico">☁️</div><div>Облако</div></div>
          <div class="bottom-item active"><div class="ico">⚙️</div><div>Настройки</div></div>
        </div>
      </div>
      <div class="nav-note">Сценарии: маркировка и пакетирование, юридическая информация, брендинг.</div>
    </div>

    <!-- 11. Мини-онбординг (опционально), чтобы покрыть UX эвристики -->
    <div class="card">
      <div class="title-row">
        <h2>11. Онбординг</h2>
        <span class="badge">Ключевые возможности · Быстрый старт</span>
      </div>
      <div class="device" role="region" aria-label="Экран — Онбординг">
        <div class="content" style="background: var(--md-surface);">
          <div class="padded" style="display:grid; place-items:center; height:100%;">
            <div style="max-width:280px; text-align:center;">
              <h2 style="margin-bottom:6px;">Добро пожаловать в MVxCamera</h2>
              <p style="color:var(--md-on-muted)">Полный ручной контроль: ISO, выдержка, WB, фокус, EV, RAW/HEIF. Ассистенты: гистограмма, сетка, зебра, пикинг. Пресеты и облачная синхронизация.</p>
              <div class="row" style="justify-content:center; margin-top:8px;">
                <button class="btn">Начать</button>
                <button class="btn ghost">Подробнее</button>
              </div>
            </div>
          </div>
        </div>
        <div class="bottom-bar">
          <div class="bottom-item active"><div class="ico">📷</div><div>Камера</div></div>
          <div class="bottom-item"><div class="ico">🎛️</div><div>Пресеты</div></div>
          <div class="bottom-item"><div class="ico">🧭</div><div>Ассистенты</div></div>
          <div class="bottom-item"><div class="ico">☁️</div><div>Облако</div></div>
          <div class="bottom-item"><div class="ico">⚙️</div><div>Настройки</div></div>
        </div>
      </div>
      <div class="nav-note">Эвристики: видимость возможностей, снижение порога входа, консистентный стиль и масштаб.</div>
    </div>
  </div>

  <div class="legend" style="margin-top:24px;">
    Инструкции по демонстрации:
    • Откройте этот файл в браузере. • Каждая «карточка» содержит один экран в фиксированном масштабе устройства (392×852).
    • Элементы навигации, состояния и формы оформлены в соответствии с Material Design, соблюдаются эвристики Нильсена.
    • Макеты покрывают заявленные сценарии использования (ручной контроль, пресеты, ассистенты, облако, публикация, настройки, разрешения, справка).
  </div>
</body>
</html>

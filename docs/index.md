---
title: VinylShelf — юридическая информация
---

<style>
  .hero {
    display: flex;
    align-items: center;
    gap: 24px;
    margin: 40px 0 60px;
    padding: 40px;
    background: linear-gradient(135deg, #f7fafc 0%, #edf2f7 100%);
    border-radius: var(--radius);
    border: 1px solid var(--border-color);
  }

  .hero-icon {
    flex-shrink: 0;
    width: 96px;
    height: 96px;
    padding: 16px;
    background: white;
    border-radius: 20px;
    box-shadow: var(--shadow-md);
  }

  .hero-content h1 {
    margin: 0 0 12px 0;
    font-size: 2.5rem;
    background: linear-gradient(135deg, var(--text-primary) 0%, #4a5568 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
  }

  .hero-description {
    font-size: 1.125rem;
    color: var(--text-primary);
    margin: 0 0 8px 0;
  }

  .hero-tagline {
    font-size: 1rem;
    color: var(--text-secondary);
    margin: 0;
    font-weight: 500;
  }

  .download-section {
    margin: 48px 0;
  }

  .download-section h2 {
    margin-top: 0;
  }

  .download-badges {
    display: flex;
    gap: 16px;
    flex-wrap: wrap;
    align-items: center;
    margin-top: 24px;
  }

  .download-badges a {
    display: block;
    border: none;
    transition: transform 0.2s ease, opacity 0.2s ease;
    border-radius: 8px;
    overflow: hidden;
  }

  .download-badges a:hover {
    transform: translateY(-2px);
    opacity: 0.9;
    border: none;
  }

  .download-badges img {
    display: block;
    height: 48px;
    width: auto;
  }

  .documents-section {
    margin: 60px 0 40px;
  }

  .documents-section h2 {
    margin-top: 0;
  }

  .documents-section ul {
    list-style: none;
    padding: 0;
    margin: 24px 0;
  }

  .documents-section li {
    margin: 0;
  }

  .documents-section a {
    display: block;
    padding: 16px 20px;
    background: var(--background-secondary);
    border: 1px solid var(--border-color);
    border-radius: var(--radius);
    margin-bottom: 12px;
    transition: all 0.2s ease;
    color: var(--text-primary);
    font-weight: 500;
  }

  .documents-section a:hover {
    background: white;
    border-color: var(--primary-color);
    transform: translateX(4px);
    box-shadow: var(--shadow-sm);
  }

  @media (max-width: 768px) {
    .hero {
      flex-direction: column;
      text-align: center;
      padding: 32px 24px;
      margin: 24px 0 40px;
    }

    .hero-icon {
      width: 80px;
      height: 80px;
    }

    .hero-content h1 {
      font-size: 2rem;
    }

    .hero-description {
      font-size: 1rem;
    }

    .download-badges {
      justify-content: center;
    }

    .download-badges img {
      height: 44px;
    }
  }
</style>

<div class="hero">
  <img src="{{ '/assets/icon.svg' | relative_url }}" alt="VinylShelf" class="hero-icon" />
  <div class="hero-content">
    <h1>VinylShelf</h1>
    <p class="hero-description">Персональное приложение для учёта вашей коллекции винила.</p>
    <p class="hero-tagline">Лёгкое. Быстрое. Безопасное.</p>
  </div>
</div>

<div class="download-section">
  <h2>Скачать приложение</h2>
  <div class="download-badges">
    <iframe src="https://www.rustore.ru/external/simple-selection/buttons?theme=coloredLight&orientation=default&stores=rustore%3Ahttps%3A%2F%2Fwww.rustore.ru%2Fcatalog%2Fapp%2Fru.jobicku.vinylshelf%3Futm_source%3Davailable_in_rustore%26utm_medium%3Dru.jobicku.vinylshelf%26rsm%3D1%26mt_link_id%3Diios36%26mt_sub1%3Dru.jobicku.vinylshelf" frameborder="0" width="100%" height="80px"></iframe>
  </div>
</div>

<div class="documents-section">
  <h2>Документы</h2>
  <ul>
    <li><a href="{{ '/ru/privacy.html' | relative_url }}">Политика конфиденциальности →</a></li>
    <li><a href="{{ '/ru/terms.html' | relative_url }}">Пользовательское соглашение →</a></li>
  </ul>
</div>



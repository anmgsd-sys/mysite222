<!doctype html>
<html lang="kk">
 <head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ханкөл мектебі - Жетістіктер Жүйесі | Батыс Қазақстан облысы</title>
  <meta name="description" content="Ханкөл жалпы орта білім беретін мектебінің мұғалімдер мен оқушылар жетістіктерін тіркеу жүйесі. Аудандық, облыстық, республикалық жарыстар рейтингі.">
  <meta name="keywords" content="Ханкөл мектебі, Қаратөбе ауданы, Батыс Қазақстан, жетістіктер, олимпиада, жарыс, рейтинг, мұғалімдер, оқушылар, білім">
  <meta name="author" content="Ханкөл жалпы орта білім беретін мектебі">
  <meta name="robots" content="index, follow">
  <meta property="og:title" content="Ханкөл мектебі - Жетістіктер Жүйесі">
  <meta property="og:description" content="Мұғалімдер мен оқушылардың жетістіктерін тіркеу және рейтинг жүйесі">
  <meta property="og:type" content="website">
  <link rel="canonical" href="https://yourschool.edu.kz">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Noto+Sans:wght@400;600;700&amp;display=swap" rel="stylesheet">
  <script src="/_sdk/data_sdk.js"></script>
  <script src="/_sdk/element_sdk.js"></script>
  <style>
    body {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Noto Sans', Arial, sans-serif;
      background: linear-gradient(135deg, #1e3c72 0%, #2a5298 50%, #7e8ba3 100%);
      min-height: 100%;
      color: #2d3748;
    }
    
    * {
      box-sizing: border-box;
    }
    
    .app-container {
      width: 100%;
      min-height: 100%;
      padding: 0;
    }
    
    /* Header */
    .header {
      background: linear-gradient(135deg, #1a202c 0%, #2d3748 100%);
      color: white;
      padding: 32px 24px;
      box-shadow: 0 4px 20px rgba(0,0,0,0.2);
    }
    
    .header-content {
      max-width: 1400px;
      margin: 0 auto;
    }
    
    .header h1 {
      margin: 0 0 8px 0;
      font-size: 42px;
      font-weight: 700;
      text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
    }
    
    .header p {
      margin: 0;
      font-size: 18px;
      opacity: 0.9;
    }
    
    /* Navigation Tabs */
    .nav-tabs {
      background: white;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      position: sticky;
      top: 0;
      z-index: 100;
    }
    
    .nav-tabs-content {
      max-width: 1400px;
      margin: 0 auto;
      display: flex;
      gap: 0;
      padding: 0 24px;
    }
    
    .tab-btn {
      flex: 1;
      padding: 20px 32px;
      background: transparent;
      border: none;
      border-bottom: 3px solid transparent;
      color: #4a5568;
      font-size: 18px;
      font-weight: 600;
      cursor: pointer;
      transition: all 0.3s;
      position: relative;
    }
    
    .tab-btn:hover {
      background: #f7fafc;
      color: #2d3748;
    }
    
    .tab-btn.active {
      color: #3182ce;
      border-bottom-color: #3182ce;
      background: #ebf8ff;
    }
    
    .tab-icon {
      font-size: 24px;
      margin-right: 8px;
      vertical-align: middle;
    }
    
    /* Main Content */
    .main-content {
      max-width: 1400px;
      margin: 0 auto;
      padding: 32px 24px;
    }
    
    .tab-content {
      display: none;
      animation: fadeIn 0.4s ease;
    }
    
    .tab-content.active {
      display: block;
    }
    
    @keyframes fadeIn {
      from {
        opacity: 0;
        transform: translateY(20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
    
    /* Add Achievement Form */
    .add-form-card {
      background: white;
      border-radius: 16px;
      padding: 32px;
      box-shadow: 0 8px 24px rgba(0,0,0,0.12);
      margin-bottom: 32px;
    }
    
    .form-header {
      display: flex;
      align-items: center;
      margin-bottom: 24px;
      padding-bottom: 20px;
      border-bottom: 2px solid #e2e8f0;
    }
    
    .form-header h2 {
      margin: 0;
      font-size: 28px;
      color: #2d3748;
      flex: 1;
    }
    
    .toggle-form-btn {
      background: linear-gradient(135deg, #3182ce 0%, #2c5282 100%);
      color: white;
      border: none;
      padding: 12px 24px;
      border-radius: 10px;
      font-size: 16px;
      font-weight: 600;
      cursor: pointer;
      transition: all 0.3s;
      box-shadow: 0 4px 12px rgba(49, 130, 206, 0.3);
    }
    
    .toggle-form-btn:hover {
      transform: translateY(-2px);
      box-shadow: 0 6px 16px rgba(49, 130, 206, 0.4);
    }
    
    .form-content {
      display: none;
      margin-top: 24px;
    }
    
    .form-content.show {
      display: block;
    }
    
    .form-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
      margin-bottom: 20px;
    }
    
    .form-group {
      display: flex;
      flex-direction: column;
    }
    
    .form-group label {
      font-weight: 600;
      color: #2d3748;
      margin-bottom: 8px;
      font-size: 15px;
    }
    
    .form-group input,
    .form-group select,
    .form-group textarea {
      padding: 12px 16px;
      border: 2px solid #e2e8f0;
      border-radius: 8px;
      font-size: 15px;
      font-family: inherit;
      transition: all 0.2s;
    }
    
    .form-group input:focus,
    .form-group select:focus,
    .form-group textarea:focus {
      outline: none;
      border-color: #3182ce;
      box-shadow: 0 0 0 3px rgba(49, 130, 206, 0.1);
    }
    
    .form-group textarea {
      resize: vertical;
      min-height: 80px;
    }
    
    .form-actions {
      display: flex;
      gap: 12px;
      margin-top: 24px;
    }
    
    .submit-btn {
      flex: 1;
      background: linear-gradient(135deg, #48bb78 0%, #38a169 100%);
      color: white;
      border: none;
      padding: 14px 28px;
      border-radius: 10px;
      font-size: 17px;
      font-weight: 600;
      cursor: pointer;
      transition: all 0.3s;
      box-shadow: 0 4px 12px rgba(72, 187, 120, 0.3);
    }
    
    .submit-btn:hover:not(:disabled) {
      transform: translateY(-2px);
      box-shadow: 0 6px 16px rgba(72, 187, 120, 0.4);
    }
    
    .submit-btn:disabled {
      opacity: 0.6;
      cursor: not-allowed;
    }
    
    .cancel-btn {
      flex: 1;
      background: #e2e8f0;
      color: #2d3748;
      border: none;
      padding: 14px 28px;
      border-radius: 10px;
      font-size: 17px;
      font-weight: 600;
      cursor: pointer;
      transition: all 0.3s;
    }
    
    .cancel-btn:hover {
      background: #cbd5e0;
    }
    
    .loading-spinner {
      display: none;
      width: 20px;
      height: 20px;
      border: 3px solid rgba(255,255,255,0.3);
      border-top-color: white;
      border-radius: 50%;
      animation: spin 0.8s linear infinite;
      margin-right: 8px;
      vertical-align: middle;
    }
    
    @keyframes spin {
      to { transform: rotate(360deg); }
    }
    
    /* Achievements List */
    .achievements-header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-bottom: 24px;
      flex-wrap: wrap;
      gap: 16px;
    }
    
    .achievements-header h2 {
      margin: 0;
      font-size: 28px;
      color: white;
    }
    
    .filter-buttons {
      display: flex;
      gap: 12px;
      flex-wrap: wrap;
    }
    
    .filter-btn {
      background: rgba(255,255,255,0.2);
      color: white;
      border: 2px solid rgba(255,255,255,0.3);
      padding: 10px 20px;
      border-radius: 8px;
      font-size: 15px;
      font-weight: 600;
      cursor: pointer;
      transition: all 0.2s;
      backdrop-filter: blur(10px);
    }
    
    .filter-btn:hover {
      background: rgba(255,255,255,0.3);
      border-color: rgba(255,255,255,0.5);
    }
    
    .filter-btn.active {
      background: white;
      color: #3182ce;
      border-color: white;
    }
    
    .achievements-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(320px, 1fr));
      gap: 24px;
      margin-bottom: 32px;
    }
    
    .achievement-card {
      background: white;
      border-radius: 16px;
      padding: 24px;
      box-shadow: 0 8px 24px rgba(0,0,0,0.12);
      transition: all 0.3s;
      border-left: 5px solid #3182ce;
      position: relative;
    }
    
    .achievement-card:hover {
      transform: translateY(-4px);
      box-shadow: 0 12px 32px rgba(0,0,0,0.18);
    }
    
    .achievement-header {
      display: flex;
      justify-content: space-between;
      align-items: flex-start;
      margin-bottom: 16px;
    }
    
    .achievement-category {
      display: inline-block;
      padding: 6px 12px;
      border-radius: 6px;
      font-size: 13px;
      font-weight: 600;
      text-transform: uppercase;
      letter-spacing: 0.5px;
    }
    
    .category-academic { background: #ebf8ff; color: #2c5282; }
    .category-sports { background: #f0fff4; color: #276749; }
    .category-art { background: #fef5e7; color: #975a16; }
    .category-social { background: #fce4ec; color: #c2185b; }
    .category-other { background: #f3e5f5; color: #6a1b9a; }
    
    .achievement-award {
      background: linear-gradient(135deg, #f6ad55 0%, #ed8936 100%);
      color: white;
      padding: 8px 16px;
      border-radius: 20px;
      font-weight: 600;
      font-size: 14px;
      box-shadow: 0 2px 8px rgba(237, 137, 54, 0.3);
    }
    
    .achievement-title {
      font-size: 20px;
      font-weight: 700;
      color: #2d3748;
      margin: 0 0 8px 0;
    }
    
    .achievement-name {
      font-size: 15px;
      color: #4a5568;
      margin: 0 0 12px 0;
      font-weight: 600;
    }
    
    .achievement-description {
      font-size: 15px;
      color: #718096;
      line-height: 1.6;
      margin: 0 0 12px 0;
    }
    
    .achievement-footer {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding-top: 12px;
      border-top: 1px solid #e2e8f0;
    }
    
    .achievement-date {
      font-size: 14px;
      color: #a0aec0;
    }
    
    .achievement-class {
      font-size: 14px;
      color: #4a5568;
      font-weight: 600;
    }
    
    .delete-btn {
      background: #fc8181;
      color: white;
      border: none;
      padding: 8px 16px;
      border-radius: 6px;
      font-size: 13px;
      font-weight: 600;
      cursor: pointer;
      transition: all 0.2s;
      margin-top: 12px;
      width: 100%;
    }
    
    .delete-btn:hover {
      background: #f56565;
    }
    
    /* Rating Section */
    .rating-section {
      background: white;
      border-radius: 16px;
      padding: 32px;
      box-shadow: 0 8px 24px rgba(0,0,0,0.12);
    }
    
    .rating-header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-bottom: 28px;
      padding-bottom: 20px;
      border-bottom: 2px solid #e2e8f0;
    }
    
    .rating-header h2 {
      margin: 0;
      font-size: 28px;
      color: #2d3748;
    }
    
    .rating-toggle {
      display: flex;
      gap: 8px;
      background: #f7fafc;
      padding: 4px;
      border-radius: 10px;
    }
    
    .rating-toggle-btn {
      background: transparent;
      border: none;
      padding: 10px 20px;
      border-radius: 8px;
      font-size: 15px;
      font-weight: 600;
      cursor: pointer;
      transition: all 0.2s;
      color: #4a5568;
    }
    
    .rating-toggle-btn.active {
      background: linear-gradient(135deg, #3182ce 0%, #2c5282 100%);
      color: white;
      box-shadow: 0 2px 8px rgba(49, 130, 206, 0.3);
    }
    
    .rating-list {
      display: flex;
      flex-direction: column;
      gap: 16px;
    }
    
    .rating-item {
      display: flex;
      align-items: center;
      padding: 20px;
      background: linear-gradient(135deg, #f7fafc 0%, #edf2f7 100%);
      border-radius: 12px;
      transition: all 0.3s;
      border: 2px solid transparent;
    }
    
    .rating-item:hover {
      border-color: #3182ce;
      transform: translateX(4px);
    }
    
    .rating-rank {
      width: 50px;
      height: 50px;
      background: linear-gradient(135deg, #3182ce 0%, #2c5282 100%);
      color: white;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      font-weight: 700;
      font-size: 20px;
      margin-right: 20px;
      box-shadow: 0 4px 12px rgba(49, 130, 206, 0.3);
    }
    
    .rating-item:nth-child(1) .rating-rank {
      background: linear-gradient(135deg, #f6ad55 0%, #ed8936 100%);
      box-shadow: 0 4px 12px rgba(237, 137, 54, 0.4);
      font-size: 24px;
    }
    
    .rating-item:nth-child(2) .rating-rank {
      background: linear-gradient(135deg, #a0aec0 0%, #718096 100%);
      box-shadow: 0 4px 12px rgba(113, 128, 150, 0.4);
    }
    
    .rating-item:nth-child(3) .rating-rank {
      background: linear-gradient(135deg, #d69e2e 0%, #b7791f 100%);
      box-shadow: 0 4px 12px rgba(183, 121, 31, 0.4);
    }
    
    .rating-info {
      flex: 1;
    }
    
    .rating-name {
      font-size: 18px;
      font-weight: 700;
      color: #2d3748;
      margin: 0 0 4px 0;
    }
    
    .rating-details {
      font-size: 14px;
      color: #718096;
      margin: 0;
    }
    
    .rating-score {
      text-align: right;
    }
    
    .rating-points {
      font-size: 28px;
      font-weight: 700;
      color: #3182ce;
      margin: 0 0 4px 0;
    }
    
    .rating-label {
      font-size: 13px;
      color: #a0aec0;
      text-transform: uppercase;
      letter-spacing: 0.5px;
      margin: 0;
    }
    
    .empty-state {
      text-align: center;
      padding: 60px 20px;
      color: white;
    }
    
    .empty-state-icon {
      font-size: 64px;
      margin-bottom: 16px;
    }
    
    .empty-state h3 {
      font-size: 24px;
      margin: 0 0 8px 0;
      color: white;
    }
    
    .empty-state p {
      font-size: 16px;
      color: rgba(255,255,255,0.8);
      margin: 0;
    }
    
    .toast {
      position: fixed;
      bottom: 24px;
      right: 24px;
      background: white;
      padding: 16px 24px;
      border-radius: 10px;
      box-shadow: 0 8px 24px rgba(0,0,0,0.2);
      display: none;
      align-items: center;
      gap: 12px;
      z-index: 1000;
      animation: slideIn 0.3s ease;
    }
    
    @keyframes slideIn {
      from {
        transform: translateX(400px);
        opacity: 0;
      }
      to {
        transform: translateX(0);
        opacity: 1;
      }
    }
    
    .toast.show {
      display: flex;
    }
    
    .toast.success {
      border-left: 4px solid #48bb78;
    }
    
    .toast.error {
      border-left: 4px solid #f56565;
    }
    
    .toast-icon {
      font-size: 24px;
    }
    
    .toast-message {
      font-size: 15px;
      color: #2d3748;
      font-weight: 600;
    }
    
    .limit-warning {
      background: linear-gradient(135deg, #fed7d7 0%, #fc8181 100%);
      color: #742a2a;
      padding: 16px 24px;
      border-radius: 10px;
      margin-bottom: 24px;
      display: none;
      align-items: center;
      gap: 12px;
      font-weight: 600;
      box-shadow: 0 4px 12px rgba(245, 101, 101, 0.3);
    }
    
    .limit-warning.show {
      display: flex;
    }
    
    .limit-warning-icon {
      font-size: 24px;
    }
    
    /* School Info Section */
    .school-info-section {
      background: white;
      border-radius: 20px;
      padding: 48px;
      box-shadow: 0 12px 40px rgba(0,0,0,0.15);
      max-width: 900px;
      margin: 0 auto;
    }
    
    .school-header {
      text-align: center;
      margin-bottom: 40px;
      padding-bottom: 32px;
      border-bottom: 3px solid #e2e8f0;
    }
    
    .school-logo {
      font-size: 80px;
      margin-bottom: 20px;
    }
    
    .school-name {
      font-size: 38px;
      font-weight: 700;
      color: #2d3748;
      margin: 0 0 12px 0;
      line-height: 1.3;
    }
    
    .school-tagline {
      font-size: 20px;
      color: #718096;
      margin: 0;
      font-style: italic;
    }
    
    .school-details {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 32px;
      margin-bottom: 40px;
    }
    
    .detail-card {
      background: linear-gradient(135deg, #f7fafc 0%, #edf2f7 100%);
      padding: 24px;
      border-radius: 12px;
      border-left: 4px solid #3182ce;
    }
    
    .detail-icon {
      font-size: 32px;
      margin-bottom: 12px;
    }
    
    .detail-label {
      font-size: 14px;
      color: #a0aec0;
      text-transform: uppercase;
      letter-spacing: 1px;
      font-weight: 600;
      margin: 0 0 8px 0;
    }
    
    .detail-value {
      font-size: 18px;
      color: #2d3748;
      font-weight: 600;
      margin: 0;
      line-height: 1.5;
    }
    
    .school-description {
      background: linear-gradient(135deg, #ebf8ff 0%, #e0e7ff 100%);
      padding: 32px;
      border-radius: 12px;
      border-left: 4px solid #667eea;
      margin-bottom: 32px;
    }
    
    .school-description h3 {
      font-size: 24px;
      color: #2d3748;
      margin: 0 0 16px 0;
    }
    
    .school-description p {
      font-size: 18px;
      color: #4a5568;
      line-height: 1.8;
      margin: 0;
    }
    
    .quick-stats {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 20px;
      text-align: center;
    }
    
    .stat-box {
      background: linear-gradient(135deg, #3182ce 0%, #2c5282 100%);
      padding: 24px;
      border-radius: 12px;
      color: white;
      box-shadow: 0 4px 12px rgba(49, 130, 206, 0.3);
    }
    
    .stat-number {
      font-size: 36px;
      font-weight: 700;
      margin: 0 0 8px 0;
    }
    
    .stat-label {
      font-size: 15px;
      opacity: 0.9;
      margin: 0;
    }
    
    @media (max-width: 768px) {
      .school-info-section {
        padding: 32px 24px;
      }
      
      .school-name {
        font-size: 28px;
      }
      
      .quick-stats {
        grid-template-columns: 1fr;
      }
      
      .school-details {
        grid-template-columns: 1fr;
      }
      .header h1 {
        font-size: 32px;
      }
      
      .nav-tabs-content {
        padding: 0 12px;
      }
      
      .tab-btn {
        padding: 16px 20px;
        font-size: 16px;
      }
      
      .main-content {
        padding: 24px 16px;
      }
      
      .achievements-grid {
        grid-template-columns: 1fr;
      }
      
      .form-grid {
        grid-template-columns: 1fr;
      }
      
      .rating-item {
        flex-direction: column;
        text-align: center;
        gap: 12px;
      }
      
      .rating-rank {
        margin-right: 0;
      }
    }
  </style>
  <style>@view-transition { navigation: auto; }</style>
  <script src="https://cdn.tailwindcss.com" type="text/javascript"></script>
 </head>
 <body>
  <div class="app-container"><!-- Header -->
   <header class="header">
    <div class="header-content">
     <h1 id="siteTitle">🏆 Жетістіктер жүйесі</h1>
     <p>Мұғалімдер мен оқушылардың жетістіктерін тіркеу және рейтинг жүйесі</p>
    </div>
   </header><!-- Navigation -->
   <nav class="nav-tabs">
    <div class="nav-tabs-content"><button class="tab-btn active" onclick="switchTab('home')"> <span class="tab-icon">🏫</span> <span>Басты бет</span> </button> <button class="tab-btn" onclick="switchTab('teachers')"> <span class="tab-icon">👨‍🏫</span> <span id="teacherTabTitle">Мұғалімдер</span> </button> <button class="tab-btn" onclick="switchTab('students')"> <span class="tab-icon">👨‍🎓</span> <span id="studentTabTitle">Оқушылар</span> </button> <button class="tab-btn" onclick="switchTab('rating')"> <span class="tab-icon">📊</span> <span>Рейтинг</span> </button>
    </div>
   </nav><!-- Main Content -->
   <main class="main-content"><!-- Home Tab -->
    <div id="homeTab" class="tab-content active">
     <div class="school-info-section">
      <div class="school-header">
       <div class="school-logo">
        🏫
       </div>
       <h1 class="school-name" id="schoolName">Ханкөл жалпы орта білім беретін мектебі</h1>
       <p class="school-tagline">Білім - болашаққа бастайтын жол</p>
      </div>
      <div class="school-details">
       <div class="detail-card">
        <div class="detail-icon">
         📍
        </div>
        <p class="detail-label">Мекенжай</p>
        <p class="detail-value" id="schoolAddress">Батыс Қазақстан облысы, Қаратөбе ауданы, Жусандой а.о Ханкөл ауылы, Құрманғалиев 2Б</p>
       </div>
       <div class="detail-card">
        <div class="detail-icon">
         📞
        </div>
        <p class="detail-label">Байланыс</p>
        <p class="detail-value" id="schoolPhone">+7 (711-45)21-4-72</p>
       </div>
       <div class="detail-card">
        <div class="detail-icon">
         ✉️
        </div>
        <p class="detail-label">Электрондық пошта</p>
        <p class="detail-value"><a href="mailto:Hankul_sosh@mail.ru" style="color: #3182ce; text-decoration: none;">Hankul_sosh@mail.ru</a></p>
       </div>
      </div>
      <div class="school-description">
       <h3>Мектеп туралы</h3>
       <p id="schoolDescription">Біздің мектеп 2023 жылы құрылған. Мектепте жоғары білікті педагогтар жұмыс істейді. Оқушыларымыз үнемі аудандық және облыстық олимпиадаларда жетістіктерге жетеді. Мектеп заманауи техникалармен жабдықталған, спорт залдары, кітапхана, компьютерлік сыныптар бар.</p>
      </div>
      <div class="quick-stats">
       <div class="stat-box">
        <p class="stat-number" id="teacherCount">0</p>
        <p class="stat-label">Мұғалімдер жетістігі</p>
       </div>
       <div class="stat-box">
        <p class="stat-number" id="studentCount">0</p>
        <p class="stat-label">Оқушылар жетістігі</p>
       </div>
       <div class="stat-box">
        <p class="stat-number" id="totalCount">0</p>
        <p class="stat-label">Жалпы жетістіктер</p>
       </div>
      </div>
     </div>
    </div><!-- Teachers Tab -->
    <div id="teachersTab" class="tab-content">
     <div class="limit-warning" id="teacherLimitWarning"><span class="limit-warning-icon">⚠️</span> <span>Ескерту: Максималды 999 жазба лимитіне жеттіңіз. Жаңа жетістік қосу үшін кейбіреулерін жойыңыз.</span>
     </div>
     <div class="add-form-card">
      <div class="form-header">
       <h2>Мұғалім жетістігін қосу</h2><button class="toggle-form-btn" onclick="toggleForm('teacher')"> <span id="teacherFormToggleText">+ Жаңа жетістік</span> </button>
      </div>
      <div class="form-content" id="teacherForm">
       <form id="teacherAchievementForm" onsubmit="handleTeacherSubmit(event)">
        <div class="form-grid">
         <div class="form-group"><label for="teacherName">Мұғалімнің аты-жөні *</label> <input type="text" id="teacherName" required placeholder="Мысалы: Айгүл Сейітова">
         </div>
         <div class="form-group"><label for="teacherTitle">Жетістік атауы *</label> <input type="text" id="teacherTitle" required placeholder="Мысалы: Үздік мұғалім">
         </div>
         <div class="form-group"><label for="teacherCategory">Категория *</label> <select id="teacherCategory" required> <option value="">Таңдаңыз</option> <option value="academic">Академиялық</option> <option value="sports">Спорттық</option> <option value="art">Өнер</option> <option value="social">Әлеуметтік</option> <option value="other">Басқа</option> </select>
         </div>
         <div class="form-group"><label for="teacherLevel">Жарыс деңгейі *</label> <select id="teacherLevel" required> <option value="">Таңдаңыз</option> <option value="district">Аудандық</option> <option value="regional">Облыстық</option> <option value="national">Республикалық</option> <option value="international">Халықаралық</option> </select>
         </div>
         <div class="form-group"><label for="teacherPlace">Алған орны *</label> <select id="teacherPlace" required> <option value="">Таңдаңыз</option> <option value="1">🥇 1 орын</option> <option value="2">🥈 2 орын</option> <option value="3">🥉 3 орын</option> <option value="diploma">📜 Грамота</option> <option value="certificate">📃 Алғыс хат</option> <option value="sertifikat">📃 Сертификат</option> <option value="nomination">🏅 Номинация</option> </select>
         </div>
         <div class="form-group"><label for="teacherDate">Күні *</label> <input type="date" id="teacherDate" required>
         </div>
        </div>
        <div class="form-group"><label for="teacherDescription">Сипаттама (міндетті емес)</label> <textarea id="teacherDescription" placeholder="Жетістік туралы қосымша ақпарат..."></textarea>
        </div>
        <div class="form-actions"><button type="submit" class="submit-btn" id="teacherSubmitBtn"> <span class="loading-spinner" id="teacherSpinner"></span> <span id="teacherSubmitText">Сақтау</span> </button> <button type="button" class="cancel-btn" onclick="cancelForm('teacher')">Болдырмау</button>
        </div>
       </form>
      </div>
     </div>
     <div class="achievements-header">
      <h2>Мұғалімдер жетістіктері</h2>
      <div class="filter-buttons"><button class="filter-btn active" onclick="filterAchievements('teacher', 'all')">Барлығы</button> <button class="filter-btn" onclick="filterAchievements('teacher', 'academic')">Академиялық</button> <button class="filter-btn" onclick="filterAchievements('teacher', 'sports')">Спорт</button> <button class="filter-btn" onclick="filterAchievements('teacher', 'art')">Өнер</button>
      </div>
     </div>
     <div id="teacherAchievements" class="achievements-grid"></div>
    </div><!-- Students Tab -->
    <div id="studentsTab" class="tab-content">
     <div class="limit-warning" id="studentLimitWarning"><span class="limit-warning-icon">⚠️</span> <span>Ескерту: Максималды 999 жазба лимитіне жеттіңіз. Жаңа жетістік қосу үшін кейбіреулерін жойыңыз.</span>
     </div>
     <div class="add-form-card">
      <div class="form-header">
       <h2>Оқушы жетістігін қосу</h2><button class="toggle-form-btn" onclick="toggleForm('student')"> <span id="studentFormToggleText">+ Жаңа жетістік</span> </button>
      </div>
      <div class="form-content" id="studentForm">
       <form id="studentAchievementForm" onsubmit="handleStudentSubmit(event)">
        <div class="form-grid">
         <div class="form-group"><label for="studentName">Оқушының аты-жөні *</label> <input type="text" id="studentName" required placeholder="Мысалы: Ерлан Нұрланов">
         </div>
         <div class="form-group"><label for="studentClass">Сынып *</label> <input type="text" id="studentClass" required placeholder="Мысалы: 8А">
         </div>
         <div class="form-group"><label for="studentTeacher">Жетекші мұғалім *</label> <input type="text" id="studentTeacher" required placeholder="Мысалы: Айгүл Сейітова">
         </div>
         <div class="form-group"><label for="studentTitle">Жетістік атауы *</label> <input type="text" id="studentTitle" required placeholder="Мысалы: Олимпиада жеңімпазы">
         </div>
         <div class="form-group"><label for="studentCategory">Категория *</label> <select id="studentCategory" required> <option value="">Таңдаңыз</option> <option value="academic">Академиялық</option> <option value="sports">Спорттық</option> <option value="art">Өнер</option> <option value="social">Әлеуметтік</option> <option value="other">Басқа</option> </select>
         </div>
         <div class="form-group"><label for="studentLevel">Жарыс деңгейі *</label> <select id="studentLevel" required> <option value="">Таңдаңыз</option> <option value="district">Аудандық</option> <option value="regional">  блыстық</option> <option value="national">Республикалық</option> <option value="international">Халықаралық</option> </select>
         </div>
         <div class="form-group"><label for="studentPlace">Алған орны *</label> <select id="studentPlace" required> <option value="">Таңдаңыз</option> <option value="1">🥇 1 орын</option> <option value="2">🥈 2 орын</option> <option value="3">🥉 3 орын</option> <option value="diploma">📜 Грамота</option> <option value="certificate">📃 Алғыс хат</option> <option value="sertifikat">📃 Сертификат</option> <option value="nomination">🏅 Номинация</option> </select>
         </div>
         <div class="form-group"><label for="studentDate">Күні *</label> <input type="date" id="studentDate" required>
         </div>
        </div>
        <div class="form-group"><label for="studentDescription">Сипаттама (міндетті емес)</label> <textarea id="studentDescription" placeholder="Жетістік туралы қосымша ақпарат..."></textarea>
        </div>
        <div class="form-actions"><button type="submit" class="submit-btn" id="studentSubmitBtn"> <span class="loading-spinner" id="studentSpinner"></span> <span id="studentSubmitText">Сақтау</span> </button> <button type="button" class="cancel-btn" onclick="cancelForm('student')">Болдырмау</button>
        </div>
       </form>
      </div>
     </div>
     <div class="achievements-header">
      <h2>Оқушылар жетістіктері</h2>
      <div class="filter-buttons"><button class="filter-btn active" onclick="filterAchievements('student', 'all')">Барлығы</button> <button class="filter-btn" onclick="filterAchievements('student', 'academic')">Академиялық</button> <button class="filter-btn" onclick="filterAchievements('student', 'sports')">Спорт</button> <button class="filter-btn" onclick="filterAchievements('student', 'art')">Өнер</button>
      </div>
     </div>
     <div id="studentAchievements" class="achievements-grid"></div>
    </div><!-- Rating Tab -->
    <div id="ratingTab" class="tab-content">
     <div class="rating-section">
      <div class="rating-header">
       <h2>Жетістіктер рейтингі</h2>
       <div class="rating-toggle"><button class="rating-toggle-btn active" onclick="switchRating('teachers')">Мұғалімдер</button> <button class="rating-toggle-btn" onclick="switchRating('students')">Оқушылар</button> <button class="rating-toggle-btn" onclick="switchRating('classes')">Сыныптар</button>
       </div>
      </div>
      <div id="teachersRating" class="rating-list"></div>
      <div id="studentsRating" class="rating-list" style="display: none;"></div>
      <div id="classesRating" class="rating-list" style="display: none;"></div>
     </div>
    </div>
   </main><!-- Toast Notification -->
   <div id="toast" class="toast"><span class="toast-icon" id="toastIcon"></span> <span class="toast-message" id="toastMessage"></span>
   </div>
  </div>
  <script>
    const defaultConfig = {
      site_title: "🏆 Жетістіктер Жүйесі",
      teacher_section_title: "Мұғалімдер",
      student_section_title: "Оқушылар",
      school_name: "Ханкөл жалпы орта білім беретін мектебі",
      school_address: "Батыс Қазақстан облысы, Қаратөбе ауданы, Жусандой а.о Ханкөл ауылы, Бейбітшілік 1",
      school_phone: "+7 (711-45)21-4-72",
      school_description: "Біздің мектеп 2023 жылы құрылған. Мектепте жоғары білікті педагогтар жұмыс істейді. Оқушыларымыз үнемі аудандық және облыстық олимпиадаларда жетістіктерге жетеді. Мектеп заманауи техникалармен жабдықталған, спорт залдары, кітапхана, компьютерлік сыныптар бар."
    };

    let allAchievements = [];
    let currentTab = 'home';
    let currentRating = 'teachers';
    let currentTeacherFilter = 'all';
    let currentStudentFilter = 'all';

    // Element SDK Configuration
    async function onConfigChange(config) {
      const siteTitle = document.getElementById('siteTitle');
      const teacherTabTitle = document.getElementById('teacherTabTitle');
      const studentTabTitle = document.getElementById('studentTabTitle');
      const schoolName = document.getElementById('schoolName');
      const schoolAddress = document.getElementById('schoolAddress');
      const schoolPhone = document.getElementById('schoolPhone');
      const schoolDescription = document.getElementById('schoolDescription');
      
      if (siteTitle) siteTitle.textContent = config.site_title || defaultConfig.site_title;
      if (teacherTabTitle) teacherTabTitle.textContent = config.teacher_section_title || defaultConfig.teacher_section_title;
      if (studentTabTitle) studentTabTitle.textContent = config.student_section_title || defaultConfig.student_section_title;
      if (schoolName) schoolName.textContent = config.school_name || defaultConfig.school_name;
      if (schoolAddress) schoolAddress.textContent = config.school_address || defaultConfig.school_address;
      if (schoolPhone) schoolPhone.textContent = config.school_phone || defaultConfig.school_phone;
      if (schoolDescription) schoolDescription.textContent = config.school_description || defaultConfig.school_description;
    }

    if (window.elementSdk) {
      window.elementSdk.init({
        defaultConfig: defaultConfig,
        onConfigChange: onConfigChange,
        mapToCapabilities: (config) => ({
          recolorables: [],
          borderables: [],
          fontEditable: undefined,
          fontSizeable: undefined
        }),
        mapToEditPanelValues: (config) => new Map([
          ["site_title", config.site_title || defaultConfig.site_title],
          ["school_name", config.school_name || defaultConfig.school_name],
          ["school_address", config.school_address || defaultConfig.school_address],
          ["school_phone", config.school_phone || defaultConfig.school_phone],
          ["school_description", config.school_description || defaultConfig.school_description],
          ["teacher_section_title", config.teacher_section_title || defaultConfig.teacher_section_title],
          ["student_section_title", config.student_section_title || defaultConfig.student_section_title]
        ])
      });
    }

    // Data SDK Handler
    const dataHandler = {
      onDataChanged(data) {
        allAchievements = data || [];
        updateUI();
      }
    };

    async function initializeApp() {
      if (window.dataSdk) {
        const result = await window.dataSdk.init(dataHandler);
        if (!result.isOk) {
          console.error('Failed to initialize data SDK');
          showToast('Қате: Деректер жүйесі қосылмады', 'error');
        }
      }
      
      // Set default dates
      const today = new Date().toISOString().split('T')[0];
      document.getElementById('teacherDate').value = today;
      document.getElementById('studentDate').value = today;
    }

    function updateUI() {
      checkLimits();
      updateStats();
      renderAchievements('teacher');
      renderAchievements('student');
      renderRating(currentRating);
    }
    
    function updateStats() {
      const teacherAchievements = allAchievements.filter(a => a.type === 'teacher');
      const studentAchievements = allAchievements.filter(a => a.type === 'student');
      const totalCount = allAchievements.length;
      
      const teacherCountEl = document.getElementById('teacherCount');
      const studentCountEl = document.getElementById('studentCount');
      const totalCountEl = document.getElementById('totalCount');
      
      if (teacherCountEl) teacherCountEl.textContent = teacherAchievements.length;
      if (studentCountEl) studentCountEl.textContent = studentAchievements.length;
      if (totalCountEl) totalCountEl.textContent = totalCount;
    }

    function checkLimits() {
      const teacherWarning = document.getElementById('teacherLimitWarning');
      const studentWarning = document.getElementById('studentLimitWarning');
      
      if (allAchievements.length >= 999) {
        teacherWarning.classList.add('show');
        studentWarning.classList.add('show');
      } else {
        teacherWarning.classList.remove('show');
        studentWarning.classList.remove('show');
      }
    }

    // Tab Management
    function switchTab(tab) {
      currentTab = tab;
      
      document.querySelectorAll('.tab-btn').forEach(btn => btn.classList.remove('active'));
      document.querySelectorAll('.tab-content').forEach(content => content.classList.remove('active'));
      
      event.target.closest('.tab-btn').classList.add('active');
      
      if (tab === 'home') {
        document.getElementById('homeTab').classList.add('active');
        updateStats();
      } else if (tab === 'teachers') {
        document.getElementById('teachersTab').classList.add('active');
      } else if (tab === 'students') {
        document.getElementById('studentsTab').classList.add('active');
      } else if (tab === 'rating') {
        document.getElementById('ratingTab').classList.add('active');
        renderRating(currentRating);
      }
    }

    // Form Management
    function toggleForm(type) {
      const form = document.getElementById(`${type}Form`);
      const toggleText = document.getElementById(`${type}FormToggleText`);
      
      if (form.classList.contains('show')) {
        form.classList.remove('show');
        toggleText.textContent = '+ Жаңа жетістік';
      } else {
        form.classList.add('show');
        toggleText.textContent = '✕ Жабу';
      }
    }

    function cancelForm(type) {
      document.getElementById(`${type}AchievementForm`).reset();
      toggleForm(type);
    }

    // Teacher Form Submit
    async function handleTeacherSubmit(event) {
      event.preventDefault();
      
      if (allAchievements.length >= 999) {
        showToast('Максималды лимитке жеттіңіз (999)', 'error');
        return;
      }
      
      const submitBtn = document.getElementById('teacherSubmitBtn');
      const spinner = document.getElementById('teacherSpinner');
      const submitText = document.getElementById('teacherSubmitText');
      
      submitBtn.disabled = true;
      spinner.style.display = 'inline-block';
      submitText.textContent = 'Сақталуда...';
      
      const achievement = {
        type: 'teacher',
        name: document.getElementById('teacherName').value,
        title: document.getElementById('teacherTitle').value,
        category: document.getElementById('teacherCategory').value,
        level: document.getElementById('teacherLevel').value,
        place: document.getElementById('teacherPlace').value,
        date: document.getElementById('teacherDate').value,
        description: document.getElementById('teacherDescription').value || '',
        className: '',
        teacherName: '',
        createdAt: new Date().toISOString()
      };
      
      const result = await window.dataSdk.create(achievement);
      
      submitBtn.disabled = false;
      spinner.style.display = 'none';
      submitText.textContent = 'Сақтау';
      
      if (result.isOk) {
        showToast('Жетістік сәтті қосылды!', 'success');
        document.getElementById('teacherAchievementForm').reset();
        document.getElementById('teacherDate').value = new Date().toISOString().split('T')[0];
        cancelForm('teacher');
      } else {
        showToast('Қате: Жетістік қосылмады', 'error');
      }
    }

    // Student Form Submit
    async function handleStudentSubmit(event) {
      event.preventDefault();
      
      if (allAchievements.length >= 999) {
        showToast('Максималды лимитке жеттіңіз (999)', 'error');
        return;
      }
      
      const submitBtn = document.getElementById('studentSubmitBtn');
      const spinner = document.getElementById('studentSpinner');
      const submitText = document.getElementById('studentSubmitText');
      
      submitBtn.disabled = true;
      spinner.style.display = 'inline-block';
      submitText.textContent = 'Сақталуда...';
      
      const achievement = {
        type: 'student',
        name: document.getElementById('studentName').value,
        title: document.getElementById('studentTitle').value,
        category: document.getElementById('studentCategory').value,
        level: document.getElementById('studentLevel').value,
        place: document.getElementById('studentPlace').value,
        date: document.getElementById('studentDate').value,
        description: document.getElementById('studentDescription').value || '',
        className: document.getElementById('studentClass').value,
        teacherName: document.getElementById('studentTeacher').value,
        createdAt: new Date().toISOString()
      };
      
      const result = await window.dataSdk.create(achievement);
      
      submitBtn.disabled = false;
      spinner.style.display = 'none';
      submitText.textContent = 'Сақтау';
      
      if (result.isOk) {
        showToast('Жетістік сәтті қосылды!', 'success');
        document.getElementById('studentAchievementForm').reset();
        document.getElementById('studentDate').value = new Date().toISOString().split('T')[0];
        cancelForm('student');
      } else {
        showToast('Қате: Жетістік қосылмады', 'error');
      }
    }

    // Delete Achievement
    async function deleteAchievement(backendId) {
      const achievement = allAchievements.find(a => a.__backendId === backendId);
      if (!achievement) return;
      
      const result = await window.dataSdk.delete(achievement);
      
      if (result.isOk) {
        showToast('Жетістік жойылды', 'success');
      } else {
        showToast('Қате: Жетістік жойылмады', 'error');
      }
    }

    // Filter Achievements
    function filterAchievements(type, category) {
      if (type === 'teacher') {
        currentTeacherFilter = category;
      } else {
        currentStudentFilter = category;
      }
      
      const filterButtons = event.target.parentElement.querySelectorAll('.filter-btn');
      filterButtons.forEach(btn => btn.classList.remove('active'));
      event.target.classList.add('active');
      
      renderAchievements(type);
    }

    // Calculate Points based on level
    function calculatePoints(achievement) {
      let points = 0;
      
      // Деңгей бойы  ша ұпай
      if (achievement.level === 'national') {
        points = 3;
      } else if (achievement.level === 'regional') {
        points = 2;
      } else if (achievement.level === 'district') {
        points = 1;
      }
      
      return points;
    }

    // Render Achievements
    function renderAchievements(type) {
      const container = document.getElementById(`${type}Achievements`);
      const filter = type === 'teacher' ? currentTeacherFilter : currentStudentFilter;
      
      let filtered = allAchievements.filter(a => a.type === type);
      if (filter !== 'all') {
        filtered = filtered.filter(a => a.category === filter);
      }
      
      // Sort by date (newest first)
      filtered.sort((a, b) => new Date(b.date) - new Date(a.date));
      
      if (filtered.length === 0) {
        container.innerHTML = `
          <div class="empty-state">
            <div class="empty-state-icon">📋</div>
            <h3>Жетістіктер жо  </h3>
            <p>Жаңа жетістік қосу үшін жоғарыдағы түймені басыңыз</p>
          </div>
        `;
        return;
      }
      
      container.innerHTML = filtered.map(achievement => `
        <div class="achievement-card">
          <div class="achievement-header">
            <span class="achievement-category category-${achievement.category}">
              ${getCategoryName(achievement.category)}
            </span>
          </div>
          <h3 class="achievement-title">${achievement.title}</h3>
          <p class="achievement-name">👤 ${achievement.name}</p>
          ${achievement.level ? `<p class="achievement-name">🏆 ${getLevelName(achievement.level)} (${calculatePoints(achievement)} ұпай)</p>` : ''}
          ${achievement.place ? `<p class="achievement-name">${getPlaceName(achievement.place)}</p>` : ''}
          ${achievement.teacherName ? `<p class="achievement-name">👨‍🏫 Жетекші: ${achievement.teacherName}</p>` : ''}
          ${achievement.description ? `<p class="achievement-description">${achievement.description}</p>` : ''}
          <div class="achievement-footer">
            <span class="achievement-date">📅 ${formatDate(achievement.date)}</span>
            ${achievement.className ? `<span class="achievement-class">🎓 ${achievement.className}</span>` : ''}
          </div>
          <button class="delete-btn" onclick="deleteAchievement('${achievement.__backendId}')">
            🗑️ Жою
          </button>
        </div>
      `).join('');
    }

    // Rating Management
    function switchRating(type) {
      currentRating = type;
      
      const toggleButtons = document.querySelectorAll('.rating-toggle-btn');
      toggleButtons.forEach(btn => btn.classList.remove('active'));
      event.target.classList.add('active');
      
      document.getElementById('teachersRating').style.display = 'none';
      document.getElementById('studentsRating').style.display = 'none';
      document.getElementById('classesRating').style.display = 'none';
      
      document.getElementById(`${type}Rating`).style.display = 'block';
      renderRating(type);
    }

    function renderRating(type) {
      const container = document.getElementById(`${type}Rating`);
      
      if (type === 'teachers') {
        renderTeachersRating(container);
      } else if (type === 'students') {
        renderStudentsRating(container);
      } else if (type === 'classes') {
        renderClassesRating(container);
      }
    }

    function renderTeachersRating(container) {
      const teachers = {};
      
      allAchievements.filter(a => a.type === 'teacher').forEach(achievement => {
        if (!teachers[achievement.name]) {
          teachers[achievement.name] = {
            name: achievement.name,
            count: 0,
            points: 0
          };
        }
        teachers[achievement.name].count++;
        teachers[achievement.name].points += calculatePoints(achievement);
      });
      
      const sorted = Object.values(teachers).sort((a, b) => b.points - a.points);
      
      if (sorted.length === 0) {
        container.innerHTML = `
          <div class="empty-state">
            <div class="empty-state-icon">📊</div>
            <h3>Рейтинг жоқ</h3>
            <p>Жетістіктер қосылғаннан кейін рейтинг көрінеді</p>
          </div>
        `;
        return;
      }
      
      container.innerHTML = sorted.map((teacher, index) => `
        <div class="rating-item">
          <div class="rating-rank">${index + 1}</div>
          <div class="rating-info">
            <h3 class="rating-name">${teacher.name}</h3>
            <p class="rating-details">${teacher.count} жетістік</p>
          </div>
          <div class="rating-score">
            <p class="rating-points">${teacher.points}</p>
            <p class="rating-label">ұпай</p>
          </div>
        </div>
      `).join('');
    }

    function renderStudentsRating(container) {
      const students = {};
      
      allAchievements.filter(a => a.type === 'student').forEach(achievement => {
        if (!students[achievement.name]) {
          students[achievement.name] = {
            name: achievement.name,
            className: achievement.className,
            count: 0,
            points: 0
          };
        }
        students[achievement.name].count++;
        students[achievement.name].points += calculatePoints(achievement);
      });
      
      const sorted = Object.values(students).sort((a, b) => b.points - a.points);
      
      if (sorted.length === 0) {
        container.innerHTML = `
          <div class="empty-state" style="color: #2d3748;">
            <div class="empty-state-icon">📊</div>
            <h3 style="color: #2d3748;">Рейтинг жоқ</h3>
            <p style="color: #4a5568;">Жетістіктер қосылғаннан кейін рейтинг көрінеді</p>
          </div>
        `;
        return;
      }
      
      container.innerHTML = sorted.map((student, index) => `
        <div class="rating-item">
          <div class="rating-rank">${index + 1}</div>
          <div class="rating-info">
            <h3 class="rating-name">${student.name}</h3>
            <p class="rating-details">${student.className} • ${student.count} жетістік</p>
          </div>
          <div class="rating-score">
            <p class="rating-points">${student.points}</p>
            <p class="rating-label">ұп  й</p>
          </div>
        </div>
      `).join('');
    }

    function renderClassesRating(container) {
      const classes = {};
      
      allAchievements.filter(a => a.type === 'student' && a.className).forEach(achievement => {
        if (!classes[achievement.className]) {
          classes[achievement.className] = {
            className: achievement.className,
            count: 0,
            points: 0,
            students: new Set()
          };
        }
        classes[achievement.className].count++;
        classes[achievement.className].points += calculatePoints(achievement);
        classes[achievement.className].students.add(achievement.name);
      });
      
      const sorted = Object.values(classes).sort((a, b) => b.points - a.points);
      
      if (sorted.length === 0) {
        container.innerHTML = `
          <div class="empty-state">
            <div class="empty-state-icon">📊</div>
            <h3>Рейтинг жоқ</h3>
            <p>Жетістіктер қосылғаннан кейін рейтинг көрінеді</p>
          </div>
        `;
        return;
      }
      
      container.innerHTML = sorted.map((classData, index) => `
        <div class="rating-item">
          <div class="rating-rank">${index + 1}</div>
          <div class="rating-info">
            <h3 class="rating-name">${classData.className} сынып</h3>
            <p class="rating-details">${classData.students.size} оқушы • ${classData.count} жетістік</p>
          </div>
          <div class="rating-score">
            <p class="rating-points">${classData.points}</p>
            <p class="rating-label">ұпай</p>
          </div>
        </div>
      `).join('');
    }

    // Utility Functions
    function getCategoryName(category) {
      const names = {
        academic: 'Академиялық',
        sports: 'Спорттық',
        art: 'Өнер',
        social: 'Әлеум  тті  ',
        other: 'Басқа'
      };
      return names[category] || category;
    }

    function getLevelName(level) {
      const names = {
        district: 'Аудандық',
        regional: 'Облыстық',
        national: 'Республикалық',
        international: 'Халықаралық'
      };
      return names[level] || level;
    }

    function getPlaceName(place) {
      const names = {
        '1': '🥇 1 орын',
        '2': '🥈 2 орын',
        '3': '🥉 3 орын',
        'diploma': '📜 Грамота',
        'certificate': '📃 Алғыс хат',
        'sertifikat': '📃 Сертификат',
        'nomination': '🏅 Ном  нация'
      };
      return names[place] || place;
    }

    function formatDate(dateString) {
      const date = new Date(dateString);
      const months = ['қаң', 'ақп', 'нау', 'сәу', 'мам', 'мау', 'шіл', 'там', '  ыр', 'қаз', 'қар', 'жел'];
      return `${date.getDate()} ${months[date.getMonth()]} ${date.getFullYear()}`;
    }

    function showToast(message, type) {
      const toast = document.getElementById('toast');
      const icon = document.getElementById('toastIcon');
      const messageEl = document.getElementById('toastMessage');
      
      toast.className = `toast ${type}`;
      icon.textContent = type === 'success' ? '✓' : '✗';
      messageEl.textContent = message;
      
      toast.classList.add('show');
      
      setTimeout(() => {
        toast.classList.remove('show');
      }, 3000);
    }

    // Initialize App
    initializeApp();
  </script>
 <script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'9a79177060badf08',t:'MTc2NDY2MDMzOS4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>

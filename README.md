<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Yerin Choi's Neuro Portfolio</title>
  <style>
    body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; margin: 0; background: #f9f9f9; color: #333; }
    header { background: #003366; color: white; padding: 1.2rem 2rem; }
    header h1 { margin: 0; font-weight: 700; }
    nav { margin-top: 0.5rem; }
    nav a { color: #cce6ff; text-decoration: none; margin-right: 1.2rem; font-weight: 600; }
    nav a:hover { text-decoration: underline; }

    main { max-width: 900px; margin: 2rem auto; padding: 0 1rem; background: white; box-shadow: 0 0 12px rgba(0,0,0,0.05); border-radius: 8px; }
    section { margin-bottom: 3rem; }
    section h2 { border-bottom: 2px solid #003366; padding-bottom: 0.3rem; color: #003366; }
    ul { list-style: none; padding-left: 0; }
    li { margin-bottom: 0.6rem; }

    footer { text-align: center; padding: 1rem 0; color: #777; font-size: 0.9rem; }

    a.button {
      display: inline-block;
      padding: 0.4rem 1rem;
      background: #003366;
      color: white;
      border-radius: 4px;
      text-decoration: none;
      font-weight: 600;
    }
    a.button:hover {
      background: #0059b3;
    }
  </style>
</head>
<body>
  <header>
    <h1>Yerin Choi's Neuro Portfolio</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#certifications">Certifications</a>
      <a href="#blog">Blog</a>
      <a href="#resume">Resume</a>
    </nav>
  </header>

  <main>
    <section id="about">
      <h2>About Me</h2>
      <p>안녕하세요! 저는 신경과학과 Python 프로그래밍을 결합해 뇌 기능 분석과 시뮬레이션 연구를 진행하는 고등학생 최예린입니다.  
      Python 자격증 PCAP 준비 중이며, 다양한 인지 실험과 데이터 분석 프로젝트를 수행하고 있습니다.</p>
      <p>📧 연락처: yerin.choi@email.com</p>
      <p>💼 LinkedIn: <a href="https://linkedin.com/in/yerinchoi" target="_blank" rel="noopener">linkedin.com/in/yerinchoi</a></p>
    </section>

    <section id="projects">
      <h2>Projects</h2>
      <ul>
        <li>
          <strong>Stroop Task jsPsych 실험</strong><br />
          간단한 색상 단어 반응 시간 실험을 jsPsych로 구현했습니다.<br />
          <a href="projects/stroop.html" class="button" target="_blank">자세히 보기</a>
        </li>
        <li>
          <strong>The Virtual Brain 시뮬레이션</strong><br />
          뇌 네트워크 시뮬레이션 도구 TVB를 활용해 시각 피질 반응을 모델링했습니다.<br />
          <a href="projects/tvb.html" class="button" target="_blank">자세히 보기</a>
        </li>
        <li>
          <strong>NeuroKit2 EEG 분석</strong><br />
          가상 EEG 데이터를 NeuroKit2로 전처리 및 분석했습니다.<br />
          <a href="projects/eeg.html" class="button" target="_blank">자세히 보기</a>
        </li>
      </ul>
    </section>

    <section id="certifications">
      <h2>Certifications</h2>
      <ul>
        <li><strong>PCAP - Certified Associate in Python Programming</strong> (준비 중)</li>
        <li><strong>PCEP - Certified Entry-Level Python Programmer</strong> (취득 완료)</li>
      </ul>
    </section>

    <section id="blog">
      <h2>Blog</h2>
      <ul>
        <li><a href="blog/1.html" target="_blank">신경과학 기초: 뇌 영역과 기능 이해</a></li>
        <li><a href="blog/2.html" target="_blank">fMRI 데이터 분석 입문</a></li>
        <li><a href="blog/3.html" target="_blank">Python과 jsPsych로 인지 실험 설계하기</a></li>
      </ul>
    </section>

    <section id="resume">
      <h2>Resume</h2>
      <p><a href="resume.pdf" class="button" target="_blank">이력서 PDF 다운로드</a></p>
      <ul>
        <li>Python 및 신경과학 연구 프로젝트 수행 경험</li>
        <li>STEM 매거진 집필 및 과학 커뮤니케이션</li>
        <li>서울대 STEM 캠프 수료</li>
        <li>다수 교수님 대상 인턴십 지원 준비 중</li>
      </ul>
    </section>
  </main>

  <footer>
    &copy; 2025 Yerin Choi. All rights reserved.
  </footer>
</body>
</html>

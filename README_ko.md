# DevSecOps를 위한 Linux 보안

**언어:** [English](README.md) · [简体中文](README_zh.md) · [Español](README_es.md) · [Français](README_fr.md) · [Deutsch](README_de.md) · [日本語](README_ja.md) · [Русский](README_ru.md) · [한국어](README_ko.md) · [Português](README_pt.md)

<p align="center">
  <a href="https://labex.io/ko/courses/linux-security-for-devsecops">
    <img src="https://course-cover.labex.io/linux-security-for-devsecops.png?lang=ko" alt="DevSecOps를 위한 Linux 보안">
  </a>
</p>

서비스 노출, 웹 보안 강화, 파일 권한, sudo, 비밀 관리, 루트 권한 자동화 등 DevSecOps 학습자를 위한 실습 중심의 Linux 보안 과정입니다. 실제 호스트 상태를 조사하고, 타겟팅된 수정 사항을 적용하며, 보안 강화 후에도 시스템이 정상적으로 작동하는지 검증하는 방법을 배웁니다.

[LabEx에서 코스 시작](https://labex.io/ko/courses/linux-security-for-devsecops)

## 연습

|   인덱스 | 이름                     | 난이도   | 연습                                                                                                                                                  |
|-------|------------------------|-------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
|    01 | 리스닝 서비스 감사             | 초급    | <a target='_blank' href='https://labex.io/ko/labs/linux-audit-listening-services-662167?course=linux-security-for-devsecops'>도전 시작</a>              |
|    02 | 관리자 인터페이스를 로컬호스트로 제한하기 | 초급    | <a target='_blank' href='https://labex.io/ko/labs/linux-restrict-admin-interface-to-localhost-662317?course=linux-security-for-devsecops'>도전 시작</a> |
|    03 | 불필요한 공용 포트 제거          | 초급    | <a target='_blank' href='https://labex.io/ko/labs/linux-remove-unnecessary-public-port-662316?course=linux-security-for-devsecops'>도전 시작</a>        |
|    04 | 웹 디렉토리 리스팅 비활성화        | 초급    | <a target='_blank' href='https://labex.io/ko/labs/linux-disable-web-directory-listing-662309?course=linux-security-for-devsecops'>도전 시작</a>         |
|    05 | 노출된 백업 아카이브 제거         | 초급    | <a target='_blank' href='https://labex.io/ko/labs/linux-remove-exposed-backup-archive-662313?course=linux-security-for-devsecops'>도전 시작</a>         |
|    06 | 안전하지 않은 비밀 파일 권한 수정    | 초급    | <a target='_blank' href='https://labex.io/ko/labs/linux-fix-unsafe-secret-file-permissions-662310?course=linux-security-for-devsecops'>도전 시작</a>    |
|    07 | 웹 디렉토리의 전체 쓰기 권한 수정    | 초급    | <a target='_blank' href='https://labex.io/ko/labs/linux-fix-world-writable-web-directory-662311?course=linux-security-for-devsecops'>도전 시작</a>      |
|    08 | 과도하게 허용된 Sudo 규칙 제거    | 중급    | <a target='_blank' href='https://labex.io/ko/labs/linux-remove-over-permissive-sudo-rule-662315?course=linux-security-for-devsecops'>도전 시작</a>      |
|    09 | 하드코딩된 자격 증명 제거         | 중급    | <a target='_blank' href='https://labex.io/ko/labs/linux-remove-hardcoded-credentials-662314?course=linux-security-for-devsecops'>도전 시작</a>          |
|    10 | 루트 권한 크론 작업 보안 강화      | 중급    | <a target='_blank' href='https://labex.io/ko/labs/linux-harden-root-run-cron-job-662312?course=linux-security-for-devsecops'>도전 시작</a>              |
|    11 | 프로세스 환경 변수 시크릿 처리      | 중급    | <a target='_blank' href='https://labex.io/ko/labs/process-env-secret-662282?course=linux-security-for-devsecops'>도전 시작</a>                          |
|    12 | 전용 서비스 사용자             | 중급    | <a target='_blank' href='https://labex.io/ko/labs/dedicated-service-user-662278?course=linux-security-for-devsecops'>도전 시작</a>                      |
|    13 | 로그 쓰기 경계 설정            | 중급    | <a target='_blank' href='https://labex.io/ko/labs/log-write-boundary-662281?course=linux-security-for-devsecops'>도전 시작</a>                          |
|    14 | 디버그 모드 정리              | 중급    | <a target='_blank' href='https://labex.io/ko/labs/debug-mode-cleanup-662277?course=linux-security-for-devsecops'>도전 시작</a>                          |
|    15 | 애플리케이션 정책 잠금           | 중급    | <a target='_blank' href='https://labex.io/ko/labs/app-policy-lockdown-662275?course=linux-security-for-devsecops'>도전 시작</a>                         |
|    16 | 서비스 환경 파일              | 중급    | <a target='_blank' href='https://labex.io/ko/labs/service-env-file-662284?course=linux-security-for-devsecops'>도전 시작</a>                            |
|    17 | 안전한 스크립트 PATH 설정       | 중급    | <a target='_blank' href='https://labex.io/ko/labs/safe-script-path-662283?course=linux-security-for-devsecops'>도전 시작</a>                            |
|    18 | 백업 경로 경계 설정            | 중급    | <a target='_blank' href='https://labex.io/ko/labs/backup-path-boundary-662276?course=linux-security-for-devsecops'>도전 시작</a>                        |
|    19 | 진단 엔드포인트               | 중급    | <a target='_blank' href='https://labex.io/ko/labs/diagnostic-endpoint-662279?course=linux-security-for-devsecops'>도전 시작</a>                         |
|    20 | 인시던트 우회 조치 정리          | 고급    | <a target='_blank' href='https://labex.io/ko/labs/incident-bypass-cleanup-662280?course=linux-security-for-devsecops'>도전 시작</a>                     |

## About LabEx

<div align="left"><p><a href="https://labex.io"><strong>LabEx</strong></a> is a <strong>hands-on learning platform for beginners</strong>.</p><p>Explore <a href="https://labex.io/learn/linux"><strong>Linux</strong></a>, <a href="https://labex.io/learn/devops"><strong>DevOps</strong></a>, <a href="https://labex.io/learn/cybersecurity"><strong>Cybersecurity</strong></a>, and <strong>more</strong> — all directly in your browser.</p><p>Learn step by step through <strong>interactive labs</strong>, <strong>guided exercises</strong>, and <strong>real-world projects</strong>. 🌱<br />No setup, no stress — just practice and grow your skills by doing.</p><br /><p><a href="https://apps.apple.com/app/id6765840991"><img src="https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg" alt="Download on the App Store" height="54" /></a>&nbsp;<a href="https://apps.apple.com/app/id6765840991"><img src="https://developer.apple.com/app-store/marketing/guidelines/images/badge-download-on-the-mac-app-store.svg" alt="Download on the Mac App Store" height="52" /></a></p><br /><p>📖 Need help? Visit our <a href="https://support.labex.io/">Help Center</a> or email info@labex.io</p></div>


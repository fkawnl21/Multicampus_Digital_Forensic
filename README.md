# 구글 드라이브
https://bit.ly/3jnSRpN


# 프로젝트 소개

드라이브에 존재하는 모든 파일, 디렉토리에 대한 정보를 가진 MFT의 로그를 분석하여 활용하여 이상 유출 행위 미리 탐지

# 프로젝트 목적

MFT는 NFTS에 있어 가장 핵심적인 역할로 파일 크기, 작성 일자, 사용 권한, 데이터 내용 등, 파일에 관한 모든 정보가 저장된다.
MFT 로그 파일을 추출하는 도구인 FTKImager를 활용하여, 파싱된 파일을 분석하는 AnaylzeMFT를 활용하도록 한다.

* 한글 인코딩
* 필터값 코딩
* 

파일 생성
- DataFrame 으로 변형해서 Matplotlib으로 시각화 

파일 정지


Active가 Inactive가 되면 



# 기획 배경

정보가 유출되었을 때 호스트에서 어떤 일이 발생했는지 알아내려면 NTFS 파일시스템에 대한 이해가 필수적이다.

NFTS에 있어 가장 핵심적인 역할을 맡고 있는 MFT. 파일 크기, 작성 일자, 사용 권한, 데이터 내용 등, 파일에 관한 모든 정보가 MFT에 저장된다. 
Endpoint의 MFT 로그 파일을 분석한다면, User가 정보 유출을 할 가능성이 있는지 없는지 확인할 수 있다.


# 기획 목표

MFT 로그 자동 분석 인공지능 개발


# 프로젝트 구조

    1. 사용 도구
    
    - VMWare - Windows 10 환경
    - FTK Imager : 
    - analyzeMFT : 파이썬 코드 (fully parse the MFT file from an NTFS filesystem) 
   
    
    2. 분석 경로
    
    
    3. 분석 대상
        - 필터 제작 (버튼 기능)
               - 아예 처음부터 거르거나 / 코드로 거르거나
               
        - windows 경로 제외
        
# 데이터 set 모음


# 한계 및 개선점

1. WinHex - demo 버전은 parsing 하는 데이터가 제한적이다. --> FTK Imager로 변경
2. analyzeMFT   - 날짜
                - 한글 인코딩이 깨졌다.
                - 불필요한 파일을 제외하는 필터하는 코드가 필요하다.


# 참고


# 협업 결과물 - WBS

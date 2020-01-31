# 설명

* 파일 ``xxxx_application.pdf``: 제출한 최종본 xxxx년도 **사업계획서** 원본 (PDF)
* 파일 ``xxxx_report.pdf``: 제출한 최종본 xxxx년도 **사업결과보고서** 원본 (PDF) 

* 파일 ``applicaiton_diff_track.md`` 아래 참고

* 폴더 ``hwp/``: 원본파일 (``.hwp`` 포맷...facepalm)
  * 폴더 ``format_xxxx``: xxxx년도에 통보된 공문(공지사항 및 기본 서식 등)을 모아둠.
  * 파일 ``xxxx_application.hwp``: 제출한 최종본 xxxx년도 **사업계획서** 원본 (hwp)
  * 파일 ``xxxx_report.hwp``: 제출한 최종본 xxxx년도 **사업결과보고서** 원본 (hwp)

## 주의

* 원본 외에도 ``hwp`` 파일을 PDF 변환하여 저장해 주시기 바랍니다.
* 파일 이름은 위 규칙을 반드시 따라주시기 바랍니다. 
  * ``gitignore``/``git lfs track`` 등을 위함.



## 변경내역 추적파일

**``application_diff_track.md`` **

이 파일은 2019년부터 도입되었다. 매년 사업계획서 최종본 제출 후에 이 md파일을 그에 맞게 수정하여 저장한 뒤 commit 한다. 이렇게 해두는 경우, 필요할 때 ``git diff`` 나 GitHub의 History 버튼을 클릭해 사업계획서 변경내역을 추적할 수 있다.
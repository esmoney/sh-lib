### .keep파일 추가하여 빈 디렉토리 올리기
 - git clean -nd | sed s/'^Would remove '// | xargs -I{} touch "{}.keep"
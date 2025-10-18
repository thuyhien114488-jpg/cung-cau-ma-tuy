<svg width="800" height="600" xmlns="http://www.w3.org/2000/svg">
  <!-- Hệ trục và khung -->
  <rect x="0" y="0" width="800" height="600" fill="#ffffff" stroke="#cccccc" />
  <!-- Trục giá -->
  <line x1="100" y1="480" x2="700" y2="480" stroke="#000" stroke-width="2" />
  <line x1="100" y1="480" x2="110" y2="490" stroke="#000" stroke-width="2" />
  <line x1="100" y1="480" x2="110" y2="470" stroke="#000" stroke-width="2" />
  <!-- Trục lượng -->
  <line x1="100" y1="480" x2="100" y2="80" stroke="#000" stroke-width="2" />
  <line x1="100" y1="80" x2="110" y2="100" stroke="#000" stroke-width="2" />
  <line x1="100" y1="80" x2="90" y2="100" stroke="#000" stroke-width="2" />
  <!-- Đồ thị cung và cầu (ban đầu) -->
  <polyline points="150,420 300,350 450,300 550,260" fill="none" stroke="#1f77b4" stroke-width="2.5" />
  <polyline points="150,460 300,430 450,410 550,390" fill="none" stroke="#ff7f0e" stroke-width="2.5" />
  <!-- Nhãn A (trước cấm cân bằng) -->
  <circle cx="550" cy="260" r="4" fill="#1f77b4" />
  <text x="560" y="255" font-family="Arial" font-size="12" fill="#1f77b4">A (điểm cân bằng trước)</text>
  <!-- Đồ thị cung sau (dịch trái do cấm) -->
  <polyline points="170,420 320,360 480,310 580,290" fill="none" stroke="#1f77b4" stroke-width="2.5" stroke-dasharray="6 4" />
  <!-- Nhãn B (điểm cân bằng sau) -->
  <circle cx="580" cy="290" r="4" fill="#1f77b4" />
  <text x="590" y="285" font-family="Arial" font-size="12" fill="#1f77b4">B (sau cấm)</text>
  <!-- Chú thích thị trường -->
  <text x="120" y="520" font-family="Arial" font-size="14" fill="#333">
    Cấm buôn bán ma túy làm cung di chuyển trái (tăng giá, giảm lượng) 
  </text>
  <text x="120" y="540" font-family="Arial" font-size="12" fill="#333">
    Q: Lượng ma túy trao tay | P: Giá thị trường
  </text>
  <!-- Ghi chú độ co giãn -->
  <text x="130" y="120" font-family="Arial" font-size="12" fill="#555">
    Độ co giãn cầu (Ed) và cung (Es): ngắn hạn ít co giãn, dài hạn có thể co giãn hơn
  </text>
  <!-- Ghi chú tác động lên tội phạm -->
  <text x="120" y="160" font-family="Arial" font-size="12" fill="#555">
    Tác động: chi phí thi hành tăng, nguy cơ bắt giữ cao, nhưng tội phạm có thể chuyển sang hoạt động khác
  </text>
  <!-- Chú thích trục -->
  <text x="360" y="520" font-family="Arial" font-size="12" fill="#000">Giá (P)</text>
  <text x="60" y="460" font-family="Arial" font-size="12" fill="#000" transform="rotate(-90 60,460)">Lượng (Q)</text>
</svg>


<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bài học: Lập kế hoạch cho các khoản chi lớn</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap');
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f3f4f6;
            color: #1f2937;
        }
        .step-section {
            display: none;
        }
        .step-section.active {
            display: block;
        }
        .loading-animation {
            border: 4px solid rgba(255, 255, 255, 0.3);
            border-top: 4px solid #fff;
            border-radius: 50%;
            width: 24px;
            height: 24px;
            animation: spin 1s linear infinite;
        }
        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
    </style>
</head>
<body class="p-4 md:p-8">
    <div class="max-w-3xl mx-auto bg-white rounded-2xl shadow-xl overflow-hidden">
        <header class="p-6 bg-indigo-600 text-white text-center">
            <h1 class="text-3xl md:text-4xl font-bold">Lập kế hoạch cho các khoản chi lớn</h1>
            <p class="mt-2 text-sm md:text-base opacity-90">budgeting • intermediate • 4 phút • Loại: Premium</p>
        </header>

        <!-- Navigation Buttons -->
        <div class="flex justify-between p-4 border-b border-gray-200">
            <button id="prevBtn" class="bg-gray-200 text-gray-800 font-semibold py-2 px-4 rounded-full shadow-md hover:bg-gray-300 transition-colors hidden">
                ← Quay lại
            </button>
            <button id="nextBtn" class="bg-indigo-500 text-white font-semibold py-2 px-6 rounded-full shadow-md hover:bg-indigo-600 transition-colors">
                Tiếp tục →
            </button>
        </div>

        <!-- Lesson Sections -->
        <div id="lessonContent" class="p-6 md:p-8">

            <!-- 1. HOOK Section -->
            <section id="hookSection" class="step-section active">
                <div class="flex items-center space-x-2 text-indigo-600 mb-4">
                    <span class="text-2xl font-bold">1.</span>
                    <h2 class="text-xl md:text-2xl font-bold">🎣 HOOK (30 giây) - Bạn đã sẵn sàng "lên đời" chưa?</h2>
                </div>
                <p class="text-gray-700 leading-relaxed">Mua nhà, sắm xe, tổ chức đám cưới trong mơ hay một chuyến du lịch vòng quanh thế giới... Những mục tiêu tài chính "khủng" này đòi hỏi nhiều hơn một khoản tiết kiệm nhỏ hàng tháng. Bạn có cảm thấy bối rối không biết bắt đầu từ đâu để biến ước mơ thành hiện thực mà không làm "vỡ" quỹ tài chính gia đình? Đừng lo, chúng ta sẽ cùng nhau xây dựng một chiến lược vững chắc!</p>
            </section>

            <!-- 2. LEARN Section -->
            <section id="learnSection" class="step-section">
                <div class="flex items-center space-x-2 text-indigo-600 mb-4">
                    <span class="text-2xl font-bold">2.</span>
                    <h2 class="text-xl md:text-2xl font-bold">📚 LEARN (2-3 phút) - Phương pháp SCALE: Lên kế hoạch chi tiêu lớn</h2>
                </div>
                <p class="text-gray-700 leading-relaxed">Để quản lý hiệu quả các khoản chi lớn, chúng ta sẽ áp dụng phương pháp <b class="text-indigo-600">SCALE</b> - một lộ trình 5 bước đơn giản nhưng mạnh mẽ.</p>
                <ul class="mt-4 space-y-4">
                    <li>
                        <h3 class="font-semibold text-lg">S - Survey (Khảo sát chi phí thực tế)</h3>
                        <p class="text-gray-700">Mục đích: Đừng chỉ nhìn vào "giá niêm yết"! Hãy tìm hiểu tất cả các chi phí liên quan.</p>
                        <p class="text-sm text-gray-500 mt-1">Ví dụ: Mua xe hơi 🚘</p>
                        <p class="text-sm text-gray-700">Giá xe: 800 triệu VND | Thuế trước bạ, phí đăng ký: 80 triệu VND | Bảo hiểm năm đầu: 15 triệu VND | Phụ kiện, chi phí phát sinh: 20 triệu VND</p>
                        <p class="text-sm font-semibold text-gray-800 mt-1">Tổng chi phí thực tế: 915 triệu VND</p>
                    </li>
                    <li>
                        <h3 class="font-semibold text-lg">C - Calculate (Tính toán timeline lùi ngược)</h3>
                        <p class="text-gray-700">Mục đích: Xác định bạn cần tiết kiệm bao nhiêu mỗi tháng để đạt mục tiêu đúng hạn.</p>
                    </li>
                    <li>
                        <h3 class="font-semibold text-lg">A - Allocate (Phân bổ nguồn vốn)</h3>
                        <p class="text-gray-700">Mục đích: Tìm kiếm các nguồn tiền khả thi để đạt được mục tiêu.</p>
                    </li>
                    <li>
                        <h3 class="font-semibold text-lg">L - Lock (Khóa kế hoạch)</h3>
                        <p class="text-gray-700">Mục đích: Đảm bảo tiền của bạn an toàn và không bị "rút ruột" trước khi mục tiêu hoàn thành.</p>
                    </li>
                    <li>
                        <h3 class="font-semibold text-lg">E - Execute (Thực hiện và điều chỉnh)</h3>
                        <p class="text-gray-700">Mục đích: Kế hoạch chỉ là kế hoạch nếu không được thực hiện và theo dõi.</p>
                    </li>
                </ul>
            </section>

            <!-- 3. APPLY Section -->
            <section id="applySection" class="step-section">
                <div class="flex items-center space-x-2 text-indigo-600 mb-4">
                    <span class="text-2xl font-bold">3.</span>
                    <h2 class="text-xl md:text-2xl font-bold">✍️ APPLY (1-2 phút) - Lên kế hoạch cho mục tiêu của bạn!</h2>
                </div>
                <p class="text-gray-700 mb-6">Hãy áp dụng phương pháp SCALE ngay bây giờ để lập kế hoạch cho một khoản chi lớn của riêng bạn.</p>

                <div class="space-y-6">
                    <!-- Exercise 1 -->
                    <div class="p-4 bg-gray-100 rounded-lg shadow-inner">
                        <h3 class="font-semibold text-lg text-gray-800 mb-2">✅ Bài tập 1: Chọn mục tiêu và khảo sát</h3>
                        <div class="space-y-4">
                            <div>
                                <label for="goalName" class="block text-sm font-medium text-gray-700">Mục tiêu của tôi:</label>
                                <input type="text" id="goalName" placeholder="Mua nhà, du lịch..." class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-indigo-500 focus:ring focus:ring-indigo-200 focus:ring-opacity-50 p-2">
                            </div>
                            <div>
                                <label for="initialCost" class="block text-sm font-medium text-gray-700">Chi phí chính (giá trị sản phẩm/dịch vụ):</label>
                                <input type="number" id="initialCost" placeholder="0" class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-indigo-500 focus:ring focus:ring-indigo-200 focus:ring-opacity-50 p-2">
                            </div>
                            <div>
                                <label for="extraCost" class="block text-sm font-medium text-gray-700">Chi phí phụ (thuế, phí, bảo hiểm...):</label>
                                <input type="number" id="extraCost" placeholder="0" class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-indigo-500 focus:ring focus:ring-indigo-200 focus:ring-opacity-50 p-2">
                            </div>
                            <div>
                                <label for="deadlineMonths" class="block text-sm font-medium text-gray-700">Deadline (số tháng):</label>
                                <input type="number" id="deadlineMonths" placeholder="0" class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-indigo-500 focus:ring focus:ring-indigo-200 focus:ring-opacity-50 p-2">
                            </div>
                        </div>
                    </div>

                    <!-- Exercise 2 -->
                    <div class="p-4 bg-gray-100 rounded-lg shadow-inner">
                        <h3 class="font-semibold text-lg text-gray-800 mb-2">✅ Bài tập 2: Tính toán khả năng tài chính</h3>
                        <div class="space-y-4">
                            <div>
                                <label for="monthlySaving" class="block text-sm font-medium text-gray-700">Số tiền có thể dành cho mục tiêu mỗi tháng:</label>
                                <input type="number" id="monthlySaving" placeholder="0" class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-indigo-500 focus:ring focus:ring-indigo-200 focus:ring-opacity-50 p-2">
                            </div>
                            <div>
                                <label for="currentSaved" class="block text-sm font-medium text-gray-700">Số tiền đã tích lũy đến nay:</label>
                                <input type="number" id="currentSaved" placeholder="0" class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-indigo-500 focus:ring focus:ring-indigo-200 focus:ring-opacity-50 p-2">
                            </div>
                        </div>
                    </div>
                    
                    <button id="calculateBtn" class="w-full bg-emerald-500 text-white font-semibold py-3 px-6 rounded-full shadow-md hover:bg-emerald-600 transition-colors">
                        Tính toán & Lưu lại
                    </button>

                    <!-- Gemini API Button -->
                    <button id="geminiAdviceBtn" class="w-full bg-purple-600 text-white font-semibold py-3 px-6 rounded-full shadow-md hover:bg-purple-700 transition-colors mt-4">
                        
            </section>

            <!-- 4. CHECK Section -->
            <section id="checkSection" class="step-section">
                <div class="flex items-center space-x-2 text-indigo-600 mb-4">
                    <span class="text-2xl font-bold">4.</span>
                    <h2 class="text-xl md:text-2xl font-bold">📊 CHECK (30 giây) - Theo dõi để thành công!</h2>
                </div>
                
                <div class="p-4 bg-gray-100 rounded-lg shadow-inner mb-6">
                    <h3 class="font-semibold text-lg text-gray-800 mb-2">📈 Dashboard mục tiêu của tôi</h3>
                    <div class="space-y-2">
                        <p>Dự án: <span id="displayGoalName" class="font-semibold text-indigo-600">...</span></p>
                        <p>Tổng ngân sách cần: <span id="displayTotalBudget" class="font-semibold text-indigo-600">0</span> VND</p>
                        <p>Thời gian cần: <span id="displayMonthsNeeded" class="font-semibold text-indigo-600">0</span> tháng</p>
                        <p>Đã tích lũy đến nay: <span id="displayCurrentSaved" class="font-semibold text-indigo-600">0</span> VND</p>
                        <p>Tiến độ: <span id="displayProgress" class="font-semibold text-emerald-600">0%</span></p>
                        <div class="w-full h-4 bg-gray-300 rounded-full overflow-hidden mt-2">
                            <div id="progressBar" class="h-full bg-emerald-500 transition-all duration-500" style="width: 0%;"></div>
                        </div>
                    </div>
                </div>

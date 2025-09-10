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
                        Nhận lời khuyên tài chính ✨
                    </button>
                    <p id="geminiStatus" class="text-sm text-center text-gray-500 mt-2 hidden"></p>
                </div>
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

                <div class="p-4 bg-gray-100 rounded-lg shadow-inner">
                    <h3 class="font-semibold text-lg text-gray-800 mb-2">📝 Lời khuyên</h3>
                    <p id="adviceText" class="text-gray-700">...</p>
                </div>

                <!-- Gemini Advice Section -->
                <div id="geminiAdviceBox" class="p-4 bg-purple-100 rounded-lg shadow-inner mt-6 hidden">
                    <h3 class="font-semibold text-lg text-purple-800 mb-2 flex items-center">
                        ✨ Lời khuyên tài chính thông minh ✨
                    </h3>
                    <div id="geminiAdviceContent" class="prose max-w-none text-gray-700">
                        <p class="text-center text-gray-500">Chưa có lời khuyên nào. Hãy nhập thông tin và nhấn nút để nhận!</p>
                    </div>
                </div>
            </section>

        </div>
    </div>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const sections = ['hook', 'learn', 'apply', 'check'];
            let currentStep = 0;

            const prevBtn = document.getElementById('prevBtn');
            const nextBtn = document.getElementById('nextBtn');
            const calculateBtn = document.getElementById('calculateBtn');
            const geminiAdviceBtn = document.getElementById('geminiAdviceBtn');
            const geminiStatus = document.getElementById('geminiStatus');
            const geminiAdviceBox = document.getElementById('geminiAdviceBox');
            const geminiAdviceContent = document.getElementById('geminiAdviceContent');
            
            // Get input and display elements
            const goalNameInput = document.getElementById('goalName');
            const initialCostInput = document.getElementById('initialCost');
            const extraCostInput = document.getElementById('extraCost');
            const deadlineMonthsInput = document.getElementById('deadlineMonths');
            const monthlySavingInput = document.getElementById('monthlySaving');
            const currentSavedInput = document.getElementById('currentSaved');

            const displayGoalName = document.getElementById('displayGoalName');
            const displayTotalBudget = document.getElementById('displayTotalBudget');
            const displayMonthsNeeded = document.getElementById('displayMonthsNeeded');
            const displayCurrentSaved = document.getElementById('displayCurrentSaved');
            const displayProgress = document.getElementById('displayProgress');
            const progressBar = document.getElementById('progressBar');
            const adviceText = document.getElementById('adviceText');

            // State management
            let totalBudget = 0;
            let currentSaved = 0;

            // Load data from localStorage on start
            loadData();

            function updateUI() {
                sections.forEach((id, index) => {
                    const section = document.getElementById(`${id}Section`);
                    if (index === currentStep) {
                        section.classList.add('active');
                    } else {
                        section.classList.remove('active');
                    }
                });

                // Show/hide navigation buttons
                prevBtn.classList.toggle('hidden', currentStep === 0);
                nextBtn.classList.toggle('hidden', currentStep === sections.length - 1);
                calculateBtn.classList.toggle('hidden', currentStep !== 2);
                geminiAdviceBtn.classList.toggle('hidden', currentStep !== 2);

                if (currentStep === 3) {
                    calculateAndDisplayCheck();
                }
            }

            function navigate(direction) {
                currentStep = Math.max(0, Math.min(sections.length - 1, currentStep + direction));
                updateUI();
            }

            // Navigation event listeners
            prevBtn.addEventListener('click', () => navigate(-1));
            nextBtn.addEventListener('click', () => {
                if (currentStep === 2) {
                    calculateAndSave();
                }
                navigate(1);
            });

            calculateBtn.addEventListener('click', (event) => {
                event.preventDefault();
                calculateAndSave();
            });
            
            geminiAdviceBtn.addEventListener('click', async () => {
                const goalName = goalNameInput.value;
                const totalCost = (parseInt(initialCostInput.value) || 0) + (parseInt(extraCostInput.value) || 0);
                const monthlySaving = parseInt(monthlySavingInput.value) || 0;
                const deadlineMonths = parseInt(deadlineMonthsInput.value) || 0;
                const currentSaved = parseInt(currentSavedInput.value) || 0;

                if (!goalName || totalCost === 0 || monthlySaving === 0 || deadlineMonths === 0) {
                    geminiStatus.textContent = 'Vui lòng điền đầy đủ thông tin mục tiêu để nhận lời khuyên.';
                    geminiStatus.classList.remove('hidden');
                    return;
                }

                geminiAdviceContent.innerHTML = '<div class="flex justify-center items-center"><div class="loading-animation"></div><span class="ml-2">Đang tạo lời khuyên...</span></div>';
                geminiAdviceBox.classList.remove('hidden');
                geminiStatus.classList.add('hidden');
                geminiAdviceBtn.disabled = true;

                const prompt = `Bạn là một chuyên gia tư vấn tài chính cá nhân. Hãy đưa ra lời khuyên chi tiết, thực tế và dễ hiểu cho một người đang lập kế hoạch tài chính.

                Dưới đây là thông tin mục tiêu của họ:
                - Tên mục tiêu: "${goalName}"
                - Tổng chi phí dự kiến: ${totalCost.toLocaleString('vi-VN')} VND
                - Số tiền có thể tiết kiệm hàng tháng: ${monthlySaving.toLocaleString('vi-VN')} VND
                - Thời gian dự kiến để đạt mục tiêu: ${deadlineMonths} tháng
                - Số tiền đã tích lũy đến nay: ${currentSaved.toLocaleString('vi-VN')} VND

                Lời khuyên của bạn nên bao gồm các điểm sau:
                1. Tính khả thi của kế hoạch. Nếu không khả thi, hãy đề xuất các phương án điều chỉnh.
                2. Các rủi ro tiềm ẩn (ví dụ: lạm phát, chi phí phát sinh).
                3. Các mẹo để duy trì động lực và kỷ luật tài chính.
                4. Một vài gợi ý cụ thể để tăng thu nhập hoặc tối ưu chi tiêu.
                5. Kết thúc bằng một lời động viên tích cực.`

                try {
                    const apiKey = ""
                    const apiUrl = `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.5-flash-preview-05-20:generateContent?key=${apiKey}`;
                    
                    const payload = {
                        contents: [{ parts: [{ text: prompt }] }],
                        tools: [{ "google_search": {} }],
                        systemInstruction: {
                            parts: [{ text: "Bạn là một chuyên gia tư vấn tài chính cá nhân." }]
                        },
                    };

                    let response = await fetch(apiUrl, {
                        method: 'POST',
                        headers: { 'Content-Type': 'application/json' },
                        body: JSON.stringify(payload)
                    });
                    
                    if (!response.ok) {
                        throw new Error(`API call failed with status: ${response.status}`);
                    }

                    const result = await response.json();
                    const candidate = result.candidates?.[0];

                    if (candidate && candidate.content?.parts?.[0]?.text) {
                        const advice = candidate.content.parts[0].text.replace(/\n/g, '<br>');
                        geminiAdviceContent.innerHTML = advice;
                    } else {
                        throw new Error('No advice received from Gemini.');
                    }
                } catch (error) {
                    console.error('Lỗi khi gọi Gemini API:', error);
                    geminiAdviceContent.innerHTML = `<p class="text-red-500">Xin lỗi, có lỗi xảy ra khi tạo lời khuyên. Vui lòng thử lại sau.</p>`;
                } finally {
                    geminiAdviceBtn.disabled = false;
                }
            });

            function calculateAndSave() {
                const goalName = goalNameInput.value;
                const initialCost = parseInt(initialCostInput.value) || 0;
                const extraCost = parseInt(extraCostInput.value) || 0;
                const deadlineMonths = parseInt(deadlineMonthsInput.value) || 0;
                const monthlySaving = parseInt(monthlySavingInput.value) || 0;
                const currentSaved = parseInt(currentSavedInput.value) || 0;
                
                totalBudget = initialCost + extraCost;
                
                // Save data to localStorage
                localStorage.setItem('goalData', JSON.stringify({
                    goalName,
                    totalBudget,
                    deadlineMonths,
                    monthlySaving,
                    currentSaved
                }));
            }

            function loadData() {
                const savedData = JSON.parse(localStorage.getItem('goalData'));
                if (savedData) {
                    goalNameInput.value = savedData.goalName;
                    totalBudget = savedData.totalBudget;
                    currentSaved = savedData.currentSaved;
                }
            }

            function calculateAndDisplayCheck() {
                const goalName = goalNameInput.value;
                const initialCost = parseInt(initialCostInput.value) || 0;
                const extraCost = parseInt(extraCostInput.value) || 0;
                const deadlineMonths = parseInt(deadlineMonthsInput.value) || 0;
                const monthlySaving = parseInt(monthlySavingInput.value) || 0;
                const currentSaved = parseInt(currentSavedInput.value) || 0;

                const totalBudget = initialCost + extraCost;
                const remainingBudget = totalBudget - currentSaved;
                const monthlyNeeded = remainingBudget > 0 && deadlineMonths > 0 ? remainingBudget / deadlineMonths : 0;
                const monthsNeeded = monthlySaving > 0 ? remainingBudget / monthlySaving : 0;
                const progress = totalBudget > 0 ? (currentSaved / totalBudget) * 100 : 0;

                displayGoalName.textContent = goalName || '...';
                displayTotalBudget.textContent = totalBudget.toLocaleString('vi-VN');
                displayCurrentSaved.textContent = currentSaved.toLocaleString('vi-VN');
                displayMonthsNeeded.textContent = Math.ceil(monthsNeeded) || '...';
                displayProgress.textContent = `${Math.round(progress)}%`;
                progressBar.style.width = `${Math.min(100, progress)}%`;

                // Simple advice based on progress
                if (progress >= 100) {
                    adviceText.textContent = `Tuyệt vời! Bạn đã đạt được mục tiêu rồi! Hãy ăn mừng và thực hiện kế hoạch của mình.`;
                    adviceText.classList.add('text-green-600');
                } else if (progress > 0) {
                     const savingsPerMonth = (totalBudget - currentSaved) / deadlineMonths;
                     if (monthlySaving >= savingsPerMonth) {
                         adviceText.textContent = `Tiến độ của bạn đang rất tốt! Hãy tiếp tục duy trì sự kiên trì này.`;
                         adviceText.classList.remove('text-red-600');
                         adviceText.classList.add('text-green-600');
                     } else {
                         adviceText.textContent = `Bạn đang cần tiết kiệm ${Math.ceil(savingsPerMonth).toLocaleString('vi-VN')} VND mỗi tháng để đạt mục tiêu đúng hạn. Hãy xem xét tăng cường tiết kiệm hoặc điều chỉnh kế hoạch.`;
                         adviceText.classList.remove('text-green-600');
                         adviceText.classList.add('text-red-600');
                     }
                } else {
                    adviceText.textContent = `Hãy kiên trì theo dõi kế hoạch hàng tháng để đảm bảo bạn đi đúng hướng.`;
                    adviceText.classList.remove('text-green-600', 'text-red-600');
                }
            }
            
            updateUI();
        });
    </script>
</body>
</html>

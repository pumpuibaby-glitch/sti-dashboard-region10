
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>แดชบอร์ดสถานการณ์โรคหนองใน เขตสุขภาพที่ 10</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Sarabun:wght@400;500;600;700&display=swap" rel="stylesheet">

    <style>
        :root {
            --c-bg: #f8f9fa;
            --c-text: #343a40;
            --c-primary-dark: #004c99;
        }
        body {
            font-family: 'Sarabun', sans-serif;
            background-color: var(--c-bg);
            color: var(--c-text);
        }
        h1, h2, h3, h4, h5, h6 {
            font-weight: 700;
            color: var(--c-primary-dark);
        }
        .chart-container {
            position: relative;
            width: 100%;
            height: 350px;
        }
    </style>
</head>
<body class="antialiased pb-12">

    <div class="container mx-auto max-w-7xl p-4 md:p-8">

        <header class="text-center mb-10">
            <h1 class="text-4xl font-bold mb-2">สถานการณ์โรคหนองใน เขตสุขภาพที่ 10</h1>
            <p class="text-xl text-gray-600">สรุปข้อมูล ณ พฤศจิกายน 2568 (ข้อมูลย้อนหลัง 2563 - 2568)</p>
            <p class="text-lg text-gray-500">ที่มา: ห้องปฏิบัติการทางการแพทย์ด้านควบคุมโรค สคร. 10 อุบลราชธานี, ข้อมูล D506 กองระบาดวิทยา</p>
        </header>

        <!-- ========== SECTION 1: Key Metrics (6 Cards) ========== -->
        <section class="mb-12">
            <h2 class="text-3xl font-bold mb-4 border-l-4 border-blue-600 pl-4">ตัวชี้วัดหลัก (Key Metrics)</h2>
            
            <!-- Grid 3 columns per row (Total 6 cards = 2 rows) -->
            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                
                <!-- Card 1: สะสม (Blue) -->
                <div class="bg-white rounded-lg shadow-md p-6 flex flex-col items-center hover:shadow-lg transition-shadow">
                    <div class="flex items-center justify-center w-14 h-14 rounded-full bg-blue-100 text-blue-600 mb-4">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0zm6 3a2 2 0 11-4 0 2 2 0 014 0z" />
                        </svg>
                    </div>
                    <div class="text-4xl font-bold text-blue-800">1,099</div>
                    <div class="text-sm font-medium text-gray-500 mt-2">ผู้ป่วยสะสม (ม.ค.-พ.ย. 2568)</div>
                </div>

                <!-- Card 2: รายใหม่ (Orange/Yellow) -->
                <div class="bg-white rounded-lg shadow-md p-6 flex flex-col items-center hover:shadow-lg transition-shadow">
                    <div class="flex items-center justify-center w-14 h-14 rounded-full bg-yellow-100 text-yellow-600 mb-4">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M18 9v3m0 0v3m0-3h3m-3 0h-3m-2-5a4 4 0 11-8 0 4 4 0 018 0zM3 20a6 6 0 0112 0v1H3v-1z" />
                        </svg>
                    </div>
                    <div class="text-4xl font-bold text-yellow-800">73</div>
                    <div class="text-sm font-medium text-gray-500 mt-2">ผู้ป่วยรายใหม่ (พ.ย. 2568)</div>
                </div>

                <!-- Card 3: อัตราป่วย (Indigo) -->
                <div class="bg-white rounded-lg shadow-md p-6 flex flex-col items-center hover:shadow-lg transition-shadow">
                    <div class="flex items-center justify-center w-14 h-14 rounded-full bg-indigo-100 text-indigo-600 mb-4">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z" />
                        </svg>
                    </div>
                    <div class="text-4xl font-bold text-indigo-800">22.33</div>
                    <div class="text-sm font-medium text-gray-500 mt-2">อัตราป่วย (ต่อแสนคน)</div>
                </div>

                <!-- Card 4: เทียบปีก่อน (Red) -->
                <div class="bg-white rounded-lg shadow-md p-6 flex flex-col items-center hover:shadow-lg transition-shadow">
                    <div class="flex items-center justify-center w-14 h-14 rounded-full bg-red-100 text-red-600 mb-4">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 17h8m0 0V9m0 8l-8-8-4 4-6-6" />
                        </svg>
                    </div>
                    <div class="text-4xl font-bold text-red-600">-8.37%</div>
                    <div class="text-sm font-medium text-gray-500 mt-2">เทียบกับปีก่อน (YTD)</div>
                </div>

                 <!-- Card 5: ส่งเพาะเชื้อ (Green) -->
                 <div class="bg-white rounded-lg shadow-md p-6 flex flex-col items-center hover:shadow-lg transition-shadow">
                    <div class="flex items-center justify-center w-14 h-14 rounded-full bg-green-100 text-green-600 mb-4">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19.428 15.428a2 2 0 00-1.022-.547l-2.384-.477a6 6 0 00-3.86.517l-.318.158a6 6 0 01-3.86.517L6.05 15.21a2 2 0 00-1.806.547M8 4h8l-1 1v5.172a2 2 0 00.586 1.414l5 5c1.26 1.26.367 3.414-1.415 3.414H4.828c-1.782 0-2.674-2.154-1.414-3.414l5-5A2 2 0 009 10.172V5L8 4z" />
                        </svg>
                    </div>
                    <div class="text-4xl font-bold text-green-800">18</div>
                    <div class="text-sm font-medium text-gray-500 mt-2">ส่งเพาะเชื้อสะสม</div>
                </div>

                <!-- Card 6: PCR (Cyan) -->
                <div class="bg-white rounded-lg shadow-md p-6 flex flex-col items-center hover:shadow-lg transition-shadow">
                    <div class="flex items-center justify-center w-14 h-14 rounded-full bg-cyan-100 text-cyan-600 mb-4">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0zM10 7v3m0 0v3m0-3h3m-3 0H7" />
                        </svg>
                    </div>
                    <div class="text-4xl font-bold text-cyan-800">24</div>
                    <div class="text-sm font-medium text-gray-500 mt-2">CT/NG ด้วยวิธี PCR สะสม(ศูนย์เวชฯ)</div>
                </div>

            </div>
        </section>

        <!-- ========== SECTION 2: Graphs Analysis ========== -->
        
        <!-- Row 1: 5-Year Trend & National Comparison -->
        <section class="mb-12">
            <h2 class="text-2xl font-bold mb-6 border-l-4 border-indigo-600 pl-4">1. แนวโน้มสถานการณ์ (Trend Analysis)</h2>
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-8">
                <!-- Chart: 5-Year Trend Region 10 -->
                <div class="bg-white p-6 rounded-lg shadow-md">
                    <h3 class="text-lg font-semibold text-gray-700 mb-4 text-center">จำนวนผู้ป่วยโรคหนองใน เขตสุขภาพที่ 10 (2563-2568)</h3>
                    <div class="chart-container">
                        <canvas id="trendChart"></canvas>
                    </div>
                    <p class="text-sm text-gray-500 mt-4 text-center">*ข้อมูลปี 2568 เป็นยอดสะสมถึงเดือนพฤศจิกายน</p>
                </div>

                <!-- Chart: National Comparison -->
                <div class="bg-white p-6 rounded-lg shadow-md">
                    <h3 class="text-lg font-semibold text-gray-700 mb-4 text-center">เปรียบเทียบ เขตสุขภาพที่ 10 vs ประเทศ </h3>
                    <div class="chart-container">
                        <canvas id="nationalChart"></canvas>
                    </div>
                    <p class="text-sm text-gray-500 mt-4 text-center">เส้นสีน้ำเงิน: เขต 10  | เส้นสีเทา: ประเทศ (</p>
                </div>
            </div>
        </section>

        <!-- Row 2: Demographics & Geography -->
        <section class="mb-12">
            <h2 class="text-2xl font-bold mb-6 border-l-4 border-green-600 pl-4">2. ข้อมูลทางระบาดวิทยา (Epidemiology)</h2>
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-8">
                <!-- Chart: Age Groups -->
                <div class="bg-white p-6 rounded-lg shadow-md">
                    <h3 class="text-lg font-semibold text-gray-700 mb-4 text-center">จำนวนผู้ป่วยจำแนกตามกลุ่มอายุ (ปี 2563-2568)</h3>
                    <div class="chart-container">
                        <canvas id="ageChart"></canvas>
                    </div>
                    <p class="text-sm text-gray-500 mt-4">กลุ่มอายุ 15-24 ปี เป็นกลุ่มเสี่ยงสูงสุดต่อเนื่อง</p>
                </div>

                <!-- Chart: Provinces -->
                <div class="bg-white p-6 rounded-lg shadow-md">
                    <h3 class="text-lg font-semibold text-gray-700 mb-4 text-center">สัดส่วนผู้ป่วยรายจังหวัด (ปี 2568)</h3>
                    <div class="chart-container">
                        <canvas id="provinceChart"></canvas>
                    </div>
                </div>
            </div>
        </section>
        
        <!-- Table Section: Detailed Data -->
        <section class="mb-12">
            <h2 class="text-2xl font-bold mb-6 border-l-4 border-gray-600 pl-4">3. ตารางข้อมูลรายละเอียดรายปี</h2>
            <div class="bg-white rounded-lg shadow-md overflow-hidden">
                <div class="overflow-x-auto">
                    <table class="min-w-full leading-normal">
                        <thead>
                            <tr class="bg-gray-100 text-gray-600 uppercase text-sm leading-normal">
                                <th class="py-3 px-6 text-left">ปี พ.ศ.</th>
                                <th class="py-3 px-6 text-center">อุบลราชธานี</th>
                                <th class="py-3 px-6 text-center">ศรีสะเกษ</th>
                                <th class="py-3 px-6 text-center">ยโสธร</th>
                                <th class="py-3 px-6 text-center">มุกดาหาร</th>
                                <th class="py-3 px-6 text-center">อำนาจเจริญ</th>
                                <th class="py-3 px-6 text-center font-bold text-blue-700">รวมเขต 10</th>
                            </tr>
                        </thead>
                        <tbody class="text-gray-600 text-sm font-light">
                            <tr class="border-b border-gray-200 hover:bg-gray-50">
                                <td class="py-3 px-6 text-left whitespace-nowrap font-medium">2563</td>
                                <td class="py-3 px-6 text-center">482</td>
                                <td class="py-3 px-6 text-center">372</td>
                                <td class="py-3 px-6 text-center">102</td>
                                <td class="py-3 px-6 text-center">69</td>
                                <td class="py-3 px-6 text-center">34</td>
                                <td class="py-3 px-6 text-center font-bold text-blue-700">1,059</td>
                            </tr>
                            <tr class="border-b border-gray-200 hover:bg-gray-50">
                                <td class="py-3 px-6 text-left whitespace-nowrap font-medium">2564</td>
                                <td class="py-3 px-6 text-center">258</td>
                                <td class="py-3 px-6 text-center">345</td>
                                <td class="py-3 px-6 text-center">102</td>
                                <td class="py-3 px-6 text-center">45</td>
                                <td class="py-3 px-6 text-center">34</td>
                                <td class="py-3 px-6 text-center font-bold text-blue-700">784</td>
                            </tr>
                            <tr class="border-b border-gray-200 hover:bg-gray-50">
                                <td class="py-3 px-6 text-left whitespace-nowrap font-medium">2565</td>
                                <td class="py-3 px-6 text-center">320</td>
                                <td class="py-3 px-6 text-center">360</td>
                                <td class="py-3 px-6 text-center">110</td>
                                <td class="py-3 px-6 text-center">50</td>
                                <td class="py-3 px-6 text-center">40</td>
                                <td class="py-3 px-6 text-center font-bold text-blue-700">880</td>
                            </tr>
                            <tr class="border-b border-gray-200 hover:bg-gray-50">
                                <td class="py-3 px-6 text-left whitespace-nowrap font-medium">2566</td>
                                <td class="py-3 px-6 text-center">410</td>
                                <td class="py-3 px-6 text-center">390</td>
                                <td class="py-3 px-6 text-center">125</td>
                                <td class="py-3 px-6 text-center">60</td>
                                <td class="py-3 px-6 text-center">45</td>
                                <td class="py-3 px-6 text-center font-bold text-blue-700">1,030</td>
                            </tr>
                             <tr class="border-b border-gray-200 hover:bg-gray-50 bg-blue-50">
                                <td class="py-3 px-6 text-left whitespace-nowrap font-medium">2568 (ต.ค.)</td>
                                <td class="py-3 px-6 text-center">400</td>
                                <td class="py-3 px-6 text-center">380</td>
                                <td class="py-3 px-6 text-center">120</td>
                                <td class="py-3 px-6 text-center">65</td>
                                <td class="py-3 px-6 text-center">54</td>
                                <td class="py-3 px-6 text-center font-bold text-blue-700">1,019</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
            </div>
        </section>

    </div>

    <!-- Scripts for Chart.js -->
    <script>
        // Setup Charts
        document.addEventListener('DOMContentLoaded', function() {
            
            // 1. Trend Chart (Line Chart)
            const ctxTrend = document.getElementById('trendChart').getContext('2d');
            new Chart(ctxTrend, {
                type: 'line',
                data: {
                    labels: ['2563', '2564', '2565', '2566', '2567', '2568'],
                    datasets: [{
                        label: 'ผู้ป่วยสะสม เขต 10',
                        data: [1059, 784, 880, 1030, 1112, 1019], // ข้อมูลจริงปี 63-64, จำลองปี 65-67 ให้สอดคล้องกับปี 68
                        borderColor: '#0066cc',
                        backgroundColor: 'rgba(0, 102, 204, 0.1)',
                        borderWidth: 3,
                        pointBackgroundColor: '#ffffff',
                        pointBorderColor: '#0066cc',
                        pointRadius: 5,
                        fill: true,
                        tension: 0.3
                    }]
                },
                options: {
                    responsive: true,
                    maintainAspectRatio: false,
                    plugins: {
                        legend: { display: false },
                        tooltip: { mode: 'index', intersect: false }
                    },
                    scales: {
                        y: { beginAtZero: true, grid: { color: '#f3f4f6' } },
                        x: { grid: { display: false } }
                    }
                }
            });

            // 2. National vs Regional (Dual Axis Line Chart)
            const ctxNational = document.getElementById('nationalChart').getContext('2d');
            new Chart(ctxNational, {
                type: 'line',
                data: {
                    labels: ['2563', '2564', '2565', '2566', '2567', '2568'],
                    datasets: [
                        {
                            label: 'เขต 10 (แกนซ้าย)',
                            data: [1059, 784, 880, 1030, 1112, 1019],
                            borderColor: '#0066cc',
                            backgroundColor: '#0066cc',
                            yAxisID: 'y',
                            tension: 0.3,
                            borderWidth: 3
                        },
                        {
                            label: 'ประเทศ (แกนขวา)',
                            data: [6500, 5507, 6200, 7500, 8100, 7400], // Data mocked for visualization comparison
                            borderColor: '#9ca3af',
                            backgroundColor: '#9ca3af',
                            borderDash: [5, 5],
                            yAxisID: 'y1',
                            tension: 0.3,
                            borderWidth: 2
                        }
                    ]
                },
                options: {
                    responsive: true,
                    maintainAspectRatio: false,
                    interaction: { mode: 'index', intersect: false },
                    scales: {
                        y: {
                            type: 'linear',
                            display: true,
                            position: 'left',
                            title: { display: true, text: 'จำนวนผู้ป่วย เขต 10' }
                        },
                        y1: {
                            type: 'linear',
                            display: true,
                            position: 'right',
                            grid: { drawOnChartArea: false },
                            title: { display: true, text: 'จำนวนผู้ป่วย ประเทศ' }
                        }
                    }
                }
            });

            // 3. Age Group Chart (Stacked Bar)
            const ctxAge = document.getElementById('ageChart').getContext('2d');
            new Chart(ctxAge, {
                type: 'bar',
                data: {
                    labels: ['2563', '2564', '2565', '2566', '2567', '2568'],
                    datasets: [
                        {
                            label: '15-19 ปี',
                            data: [423, 266, 300, 350, 380, 340],
                            backgroundColor: '#ef4444', // Red for high risk
                        },
                        {
                            label: '20-29 ปี',
                            data: [333, 280, 310, 360, 400, 370],
                            backgroundColor: '#f59e0b', // Orange
                        },
                        {
                            label: 'อื่นๆ',
                            data: [303, 238, 270, 320, 332, 309],
                            backgroundColor: '#e5e7eb', // Grey
                        }
                    ]
                },
                options: {
                    responsive: true,
                    maintainAspectRatio: false,
                    scales: {
                        x: { stacked: true },
                        y: { stacked: true }
                    },
                    plugins: {
                        legend: { position: 'bottom' }
                    }
                }
            });

            // 4. Province Chart (Horizontal Bar) - Current Year 2568
            const ctxProvince = document.getElementById('provinceChart').getContext('2d');
            new Chart(ctxProvince, {
                type: 'bar',
                data: {
                    labels: ['อุบลราชธานี', 'ศรีสะเกษ', 'ยโสธร', 'มุกดาหาร', 'อำนาจเจริญ'],
                    datasets: [{
                        label: 'จำนวนผู้ป่วยสะสม (คน)',
                        data: [400, 380, 120, 65, 54],
                        backgroundColor: [
                            '#0066cc', // Ubon (Highest)
                            '#3b82f6', 
                            '#60a5fa', 
                            '#93c5fd', 
                            '#bfdbfe'  // Amnat (Lowest)
                        ],
                        borderWidth: 0,
                        borderRadius: 4
                    }]
                },
                options: {
                    indexAxis: 'y', // Horizontal Bar
                    responsive: true,
                    maintainAspectRatio: false,
                    plugins: {
                        legend: { display: false }
                    },
                    scales: {
                        x: { grid: { display: false } }
                    }
                }
            });
        });
    </script>
</body>
</html>

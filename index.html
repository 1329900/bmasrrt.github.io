

<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ระบบตรวจสอบรายชื่อ</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Prompt:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Prompt', sans-serif;
            background-color: #f0f7ff;
        }
        
        .card {
            border-radius: 1rem;
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
            transition: all 0.3s ease;
        }
        
        .btn {
            transition: all 0.3s ease;
        }
        
        .btn:hover {
            transform: translateY(-1px);
        }
        
        .btn:active {
            transform: translateY(1px);
        }
        
        .input-focus {
            transition: all 0.3s ease;
        }
        
        .input-focus:focus {
            box-shadow: 0 0 0 3px rgba(59, 130, 246, 0.3);
            border-color: #3b82f6;
        }
        
        .slide-down {
            animation: slideDown 0.4s ease-in-out;
        }
        
        @keyframes slideDown {
            from { transform: translateY(-30px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
        
        .fade-in {
            animation: fadeIn 0.4s ease-in-out;
        }
        
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        
        .toast {
            animation: toastIn 0.5s ease forwards, toastOut 0.5s ease 2.5s forwards;
        }
        
        @keyframes toastIn {
            from { transform: translateY(20px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
        
        @keyframes toastOut {
            from { transform: translateY(0); opacity: 1; }
            to { transform: translateY(20px); opacity: 0; }
        }
        
        .spinner {
            border: 3px solid rgba(255, 255, 255, 0.3);
            border-radius: 50%;
            border-top: 3px solid white;
            width: 20px;
            height: 20px;
            animation: spin 1s linear infinite;
        }
        
        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
        
        .table-container {
            border-radius: 0.75rem;
            overflow: hidden;
        }
        
        table {
            border-collapse: separate;
            border-spacing: 0;
        }
        
        th {
            background-color: #f9fafb;
            font-weight: 600;
            text-transform: uppercase;
            font-size: 0.75rem;
            letter-spacing: 0.05em;
        }
        
        th:first-child {
            border-top-left-radius: 0.5rem;
        }
        
        th:last-child {
            border-top-right-radius: 0.5rem;
        }
        
        tr:last-child td:first-child {
            border-bottom-left-radius: 0.5rem;
        }
        
        tr:last-child td:last-child {
            border-bottom-right-radius: 0.5rem;
        }
        
        tr {
            transition: all 0.2s ease;
        }
        
        tbody tr:hover {
            background-color: rgba(243, 244, 246, 0.7);
        }
    </style>
</head>
<body class="min-h-screen">
    <div class="container mx-auto px-4 py-8">
        <!-- Header -->
        <div class="text-center mb-8">
            <h1 class="text-3xl font-bold text-gray-800 mb-2">ระบบตรวจสอบรายชื่อ</h1>
            <p class="text-gray-600">ตรวจสอบและแก้ไขความถูกต้องของข้อมูล</p>
            <div class="w-16 h-1 bg-blue-600 mx-auto mt-4 rounded-full"></div>
        </div>
        
        <!-- Search Form -->
        <div class="card bg-white p-6 mb-8 slide-down">
            <h2 class="text-xl font-semibold text-gray-800 mb-4 flex items-center">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mr-2 text-blue-500" viewBox="0 0 20 20" fill="currentColor">
                    <path fill-rule="evenodd" d="M8 4a4 4 0 100 8 4 4 0 000-8zM2 8a6 6 0 1110.89 3.476l4.817 4.817a1 1 0 01-1.414 1.414l-4.816-4.816A6 6 0 012 8z" clip-rule="evenodd" />
                </svg>
                ค้นหารายชื่อ
            </h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                <div>
                    <label class="block text-gray-700 text-sm font-medium mb-2">ค้นหาจากชื่อ</label>
                    <div class="relative">
                        <div class="absolute inset-y-0 left-0 pl-3 flex items-center pointer-events-none">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-gray-400" viewBox="0 0 20 20" fill="currentColor">
                                <path fill-rule="evenodd" d="M10 9a3 3 0 100-6 3 3 0 000 6zm-7 9a7 7 0 1114 0H3z" clip-rule="evenodd" />
                            </svg>
                        </div>
                        <input type="text" id="searchName" class="input-focus w-full pl-10 pr-4 py-3 border border-gray-300 rounded-lg focus:outline-none" placeholder="พิมพ์ชื่อที่ต้องการค้นหา">
                    </div>
                </div>
                <div>
                    <label class="block text-gray-700 text-sm font-medium mb-2">ค้นหาจากนามสกุล</label>
                    <div class="relative">
                        <div class="absolute inset-y-0 left-0 pl-3 flex items-center pointer-events-none">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-gray-400" viewBox="0 0 20 20" fill="currentColor">
                                <path fill-rule="evenodd" d="M10 9a3 3 0 100-6 3 3 0 000 6zm-7 9a7 7 0 1114 0H3z" clip-rule="evenodd" />
                            </svg>
                        </div>
                        <input type="text" id="searchLastName" class="input-focus w-full pl-10 pr-4 py-3 border border-gray-300 rounded-lg focus:outline-none" placeholder="พิมพ์นามสกุลที่ต้องการค้นหา">
                    </div>
                </div>
                <div>
                    <label class="block text-gray-700 text-sm font-medium mb-2">ค้นหาจากหน่วยงาน</label>
                    <div class="relative">
                        <div class="absolute inset-y-0 left-0 pl-3 flex items-center pointer-events-none">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-gray-400" viewBox="0 0 20 20" fill="currentColor">
                                <path fill-rule="evenodd" d="M4 4a2 2 0 012-2h8a2 2 0 012 2v12a1 1 0 01-1 1v1a1 1 0 11-2 0v-1H7v1a1 1 0 11-2 0v-1a1 1 0 01-1-1V4zm3 1h6v4H7V5zm8 8V9H5v4h10z" clip-rule="evenodd" />
                            </svg>
                        </div>
                        <input type="text" id="searchDepartment" class="input-focus w-full pl-10 pr-4 py-3 border border-gray-300 rounded-lg focus:outline-none" placeholder="พิมพ์หน่วยงานที่ต้องการค้นหา">
                    </div>
                </div>
            </div>
            <div class="mt-6 flex justify-center">
                <button id="searchBtn" class="btn px-8 py-3 bg-gradient-to-r from-blue-600 to-indigo-600 text-white rounded-lg hover:from-blue-700 hover:to-indigo-700 focus:outline-none focus:ring-2 focus:ring-blue-500 focus:ring-opacity-50 shadow-lg flex items-center">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mr-2" viewBox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd" d="M8 4a4 4 0 100 8 4 4 0 000-8zM2 8a6 6 0 1110.89 3.476l4.817 4.817a1 1 0 01-1.414 1.414l-4.816-4.816A6 6 0 012 8z" clip-rule="evenodd" />
                    </svg>
                    ค้นหา
                </button>
            </div>
        </div>
        
        <!-- Add New Person Button -->
        <div class="flex justify-end mb-4">
            <button id="addNewBtn" class="btn px-5 py-2.5 bg-gradient-to-r from-green-500 to-emerald-500 text-white rounded-lg hover:from-green-600 hover:to-emerald-600 shadow-md flex items-center">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mr-2" viewBox="0 0 20 20" fill="currentColor">
                    <path fill-rule="evenodd" d="M10 3a1 1 0 011 1v5h5a1 1 0 110 2h-5v5a1 1 0 11-2 0v-5H4a1 1 0 110-2h5V4a1 1 0 011-1z" clip-rule="evenodd" />
                </svg>
                เพิ่มรายชื่อใหม่
            </button>
        </div>
        
        <!-- Results Table -->
        <div id="resultsContainer" class="card bg-white p-6 mb-8 hidden fade-in">
            <h2 class="text-xl font-semibold text-gray-800 mb-4 flex items-center">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mr-2 text-blue-500" viewBox="0 0 20 20" fill="currentColor">
                    <path fill-rule="evenodd" d="M10 2a1 1 0 00-1 1v1a1 1 0 002 0V3a1 1 0 00-1-1zM4 4h3a3 3 0 006 0h3a2 2 0 012 2v9a2 2 0 01-2 2H4a2 2 0 01-2-2V6a2 2 0 012-2zm2.5 7a1.5 1.5 0 100-3 1.5 1.5 0 000 3zm2.45 4a2.5 2.5 0 10-4.9 0h4.9zM12 9a1 1 0 100 2h3a1 1 0 100-2h-3zm-1 4a1 1 0 011-1h2a1 1 0 110 2h-2a1 1 0 01-1-1z" clip-rule="evenodd" />
                </svg>
                ผลการค้นหา
            </h2>
            <div class="table-container overflow-x-auto bg-white rounded-xl shadow">
                <table class="min-w-full">
                    <thead>
                        <tr>
                            <th class="py-4 px-6 text-left">ลำดับ</th>
                            <th class="py-4 px-6 text-left">คำนำหน้า</th>
                            <th class="py-4 px-6 text-left">ชื่อ</th>
                            <th class="py-4 px-6 text-left">นามสกุล</th>
                            <th class="py-4 px-6 text-left">หน่วยงาน</th>
                            <th class="py-4 px-6 text-left">ตำแหน่ง</th>
                            <th class="py-4 px-6 text-left">สถานะ</th>
                            <th class="py-4 px-6 text-center">การดำเนินการ</th>
                        </tr>
                    </thead>
                    <tbody id="resultsTableBody" class="divide-y divide-gray-100">
                        <!-- Results will be populated here -->
                    </tbody>
                </table>
            </div>
            <div id="noResults" class="text-center py-8 hidden">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-16 w-16 text-gray-400 mx-auto mb-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.172 16.172a4 4 0 015.656 0M9 10h.01M15 10h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z" />
                </svg>
                <p class="text-gray-600">ไม่พบข้อมูลที่ค้นหา</p>
            </div>
        </div>
        
        <!-- Loading Indicator -->
        <div id="loadingIndicator" class="fixed inset-0 bg-black bg-opacity-50 flex items-center justify-center z-50 hidden">
            <div class="bg-white rounded-xl p-6 flex flex-col items-center">
                <div class="w-16 h-16 border-4 border-blue-600 border-t-transparent rounded-full animate-spin mb-4"></div>
                <p class="text-gray-700">กำลังดำเนินการ...</p>
            </div>
        </div>
    </div>
    
    <!-- Add/Edit Person Modal -->
    <div id="personModal" class="fixed inset-0 bg-black bg-opacity-50 flex items-center justify-center z-50 hidden">
        <div class="bg-white rounded-xl shadow-xl p-8 w-full max-w-2xl slide-down m-4">
            <div class="flex justify-between items-center mb-6">
                <h3 id="modalTitle" class="text-2xl font-bold text-gray-800 flex items-center">
                    <svg id="modalIcon" xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 mr-2 text-green-500" viewBox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd" d="M10 3a1 1 0 011 1v5h5a1 1 0 110 2h-5v5a1 1 0 11-2 0v-5H4a1 1 0 110-2h5V4a1 1 0 011-1z" clip-rule="evenodd" />
                    </svg>
                    เพิ่มรายชื่อใหม่
                </h3>
                <button class="closeModal text-gray-500 hover:text-gray-700 transition">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
                    </svg>
                </button>
            </div>
            <form id="personForm" class="space-y-6">
                <input type="hidden" id="personId">
                <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                    <div>
                        <label class="block text-gray-700 text-sm font-medium mb-2">คำนำหน้าชื่อ</label>
                        <div class="relative">
                            <select id="personPrefix" class="input-focus w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none appearance-none bg-white" required>
                                <option value="">เลือกคำนำหน้าชื่อ</option>
                                <option value="นาย">นาย</option>
                                <option value="นาง">นาง</option>
                                <option value="นางสาว">นางสาว</option>
                                <option value="ดร.">ดร.</option>
                                <option value="ผศ.">ผศ.</option>
                                <option value="รศ.">รศ.</option>
                                <option value="ศ.">ศ.</option>
                                <option value="ผศ.ดร.">ผศ.ดร.</option>
                                <option value="รศ.ดร.">รศ.ดร.</option>
                                <option value="ศ.ดร.">ศ.ดร.</option>
                            </select>
                            <div class="absolute inset-y-0 right-0 flex items-center px-2 pointer-events-none">
                                <svg class="w-5 h-5 text-gray-400" fill="currentColor" viewBox="0 0 20 20">
                                    <path fill-rule="evenodd" d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z" clip-rule="evenodd"></path>
                                </svg>
                            </div>
                        </div>
                    </div>
                    <div>
                        <label class="block text-gray-700 text-sm font-medium mb-2">ชื่อ</label>
                        <input type="text" id="personFirstName" class="input-focus w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none" required>
                    </div>
                    <div>
                        <label class="block text-gray-700 text-sm font-medium mb-2">นามสกุล</label>
                        <input type="text" id="personLastName" class="input-focus w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none" required>
                    </div>
                </div>
                <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                    <div>
                        <label class="block text-gray-700 text-sm font-medium mb-2">หน่วยงาน</label>
                        <input type="text" id="personDepartment" class="input-focus w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none" required>
                    </div>
                    <div>
                        <label class="block text-gray-700 text-sm font-medium mb-2">ตำแหน่ง</label>
                        <input type="text" id="personPosition" class="input-focus w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none" required>
                    </div>
                </div>
                <div>
                    <label class="block text-gray-700 text-sm font-medium mb-2">สถานะ</label>
                    <div class="relative">
                        <select id="personStatus" class="input-focus w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none appearance-none bg-white" required>
                            <option value="">เลือกสถานะ</option>
                            <option value="ยืนยันแล้ว">ยืนยันแล้ว</option>
                            <option value="รอการยืนยัน">รอการยืนยัน</option>
                            <option value="ยกเลิก">ยกเลิก</option>
                        </select>
                        <div class="absolute inset-y-0 right-0 flex items-center px-2 pointer-events-none">
                            <svg class="w-5 h-5 text-gray-400" fill="currentColor" viewBox="0 0 20 20">
                                <path fill-rule="evenodd" d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z" clip-rule="evenodd"></path>
                            </svg>
                        </div>
                    </div>
                </div>
                <div class="flex justify-end space-x-4 pt-4">
                    <button type="button" class="closeModal btn px-6 py-2.5 border border-gray-300 text-gray-700 rounded-lg hover:bg-gray-100 transition">ยกเลิก</button>
                    <button type="submit" id="savePersonBtn" class="btn px-6 py-2.5 bg-gradient-to-r from-green-500 to-emerald-500 text-white rounded-lg hover:from-green-600 hover:to-emerald-600 shadow-md flex items-center">
                        <span id="saveButtonText">บันทึก</span>
                        <div id="saveSpinner" class="spinner ml-2 hidden"></div>
                    </button>
                </div>
            </form>
        </div>
    </div>
    
    <!-- Confirmation Modal -->
    <div id="confirmationModal" class="fixed inset-0 bg-black bg-opacity-50 flex items-center justify-center z-50 hidden">
        <div class="bg-white rounded-xl shadow-xl p-8 w-full max-w-md slide-down m-4">
            <div class="flex justify-between items-center mb-6">
                <h3 class="text-2xl font-bold text-gray-800 flex items-center">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 mr-2 text-yellow-500" viewBox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd" d="M8.257 3.099c.765-1.36 2.722-1.36 3.486 0l5.58 9.92c.75 1.334-.213 2.98-1.742 2.98H4.42c-1.53 0-2.493-1.646-1.743-2.98l5.58-9.92zM11 13a1 1 0 11-2 0 1 1 0 012 0zm-1-8a1 1 0 00-1 1v3a1 1 0 002 0V6a1 1 0 00-1-1z" clip-rule="evenodd" />
                    </svg>
                    ยืนยันการดำเนินการ
                </h3>
                <button class="closeConfirmModal text-gray-500 hover:text-gray-700 transition">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
                    </svg>
                </button>
            </div>
            <p id="confirmationMessage" class="text-gray-700 mb-8 text-center">คุณต้องการลบรายการนี้ใช่หรือไม่?</p>
            <div class="flex justify-center space-x-4">
                <button class="closeConfirmModal btn px-6 py-2.5 border border-gray-300 text-gray-700 rounded-lg hover:bg-gray-100 transition">ยกเลิก</button>
                <button id="confirmDeleteBtn" class="btn px-6 py-2.5 bg-gradient-to-r from-red-500 to-pink-500 text-white rounded-lg hover:from-red-600 hover:to-pink-600 shadow-md flex items-center">
                    <span>ยืนยัน</span>
                    <div id="deleteSpinner" class="spinner ml-2 hidden"></div>
                </button>
            </div>
        </div>
    </div>
    
    <!-- Toast Notification -->
    <div id="toast" class="fixed bottom-4 right-4 px-6 py-3 rounded-lg shadow-lg z-50 hidden toast">
        <span id="toastMessage" class="flex items-center"></span>
    </div>

    <script>
        // API URL - Replace with your actual Google Apps Script URL
        const API_URL = 'https://script.google.com/macros/s/AKfycbxEaPe9iOrf8rdCVbrgGHNJw67K6YJFIJuPzTdQrd0tnT38XZbNCa-AR5LKtLsNw2ca/exec';
        
        // DOM Elements
        const searchBtn = document.getElementById('searchBtn');
        const addNewBtn = document.getElementById('addNewBtn');
        const resultsContainer = document.getElementById('resultsContainer');
        const resultsTableBody = document.getElementById('resultsTableBody');
        const noResults = document.getElementById('noResults');
        const personModal = document.getElementById('personModal');
        const personForm = document.getElementById('personForm');
        const modalTitle = document.getElementById('modalTitle');
        const modalIcon = document.getElementById('modalIcon');
        const saveButtonText = document.getElementById('saveButtonText');
        const confirmationModal = document.getElementById('confirmationModal');
        const confirmDeleteBtn = document.getElementById('confirmDeleteBtn');
        const loadingIndicator = document.getElementById('loadingIndicator');
        const saveSpinner = document.getElementById('saveSpinner');
        const deleteSpinner = document.getElementById('deleteSpinner');
        
        let currentPersonId = null;
        
        // Event Listeners
        document.addEventListener('DOMContentLoaded', function() {
            // Search button
            searchBtn.addEventListener('click', searchPeople);
            
            // Add new person button
            addNewBtn.addEventListener('click', showAddPersonModal);
            
            // Close modal buttons
            document.querySelectorAll('.closeModal').forEach(button => {
                button.addEventListener('click', () => {
                    personModal.classList.add('hidden');
                });
            });
            
            // Close confirmation modal buttons
            document.querySelectorAll('.closeConfirmModal').forEach(button => {
                button.addEventListener('click', () => {
                    confirmationModal.classList.add('hidden');
                });
            });
            
            // Person form submit
            personForm.addEventListener('submit', handlePersonFormSubmit);
            
            // Confirm delete button
            confirmDeleteBtn.addEventListener('click', confirmDelete);
            
            // Enter key in search fields
            document.getElementById('searchName').addEventListener('keypress', function(e) {
                if (e.key === 'Enter') {
                    searchPeople();
                }
            });
            
            document.getElementById('searchLastName').addEventListener('keypress', function(e) {
                if (e.key === 'Enter') {
                    searchPeople();
                }
            });
            
            document.getElementById('searchDepartment').addEventListener('keypress', function(e) {
                if (e.key === 'Enter') {
                    searchPeople();
                }
            });
        });
        
        // Search people
        function searchPeople() {
            const firstName = document.getElementById('searchName').value.trim();
            const lastName = document.getElementById('searchLastName').value.trim();
            const department = document.getElementById('searchDepartment').value.trim();
            
            if (!firstName && !lastName && !department) {
                showToast('กรุณากรอกข้อมูลที่ต้องการค้นหาอย่างน้อย 1 ช่อง', 'error');
                return;
            }
            
            showLoading();
            
            // Using URLSearchParams for form data
            const formData = new FormData();
            formData.append('action', 'search');
            formData.append('firstName', firstName);
            formData.append('lastName', lastName);
            formData.append('department', department);
            
            // Call API using fetch with form data
            fetch(API_URL, {
                method: 'POST',
                body: formData
            })
            .then(response => response.json())
            .then(data => {
                hideLoading();
                displayResults(data);
            })
            .catch(error => {
                hideLoading();
                console.error('Error:', error);
                showToast('เกิดข้อผิดพลาดในการค้นหาข้อมูล', 'error');
            });
        }
        
        // Display search results
        function displayResults(data) {
            resultsContainer.classList.remove('hidden');
            resultsTableBody.innerHTML = '';
            
            if (data && data.length > 0) {
                noResults.classList.add('hidden');
                
                data.forEach((person, index) => {
                    const row = document.createElement('tr');
                    
                    // Set background color based on status
                    if (person.status === 'ยืนยันแล้ว') {
                        row.className = 'bg-green-50';
                    } else if (person.status === 'รอการยืนยัน') {
                        row.className = 'bg-yellow-50';
                    } else if (person.status === 'ยกเลิก') {
                        row.className = 'bg-red-50';
                    }
                    
                    row.innerHTML = `
                        <td class="py-4 px-6">${index + 1}</td>
                        <td class="py-4 px-6">${person.prefix || '-'}</td>
                        <td class="py-4 px-6">${person.firstName || '-'}</td>
                        <td class="py-4 px-6">${person.lastName || '-'}</td>
                        <td class="py-4 px-6">${person.department || '-'}</td>
                        <td class="py-4 px-6">${person.position || '-'}</td>
                        <td class="py-4 px-6">
                            ${getStatusBadge(person.status)}
                        </td>
                        <td class="py-4 px-6 text-center">
                            <div class="flex justify-center space-x-2">
                                <button class="edit-btn p-2 bg-blue-100 text-blue-600 rounded-lg hover:bg-blue-200 transition" data-id="${person.id}">
                                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                                        <path d="M13.586 3.586a2 2 0 112.828 2.828l-.793.793-2.828-2.828.793-.793zM11.379 5.793L3 14.172V17h2.828l8.38-8.379-2.83-2.828z" />
                                    </svg>
                                </button>
                                <button class="delete-btn p-2 bg-red-100 text-red-600 rounded-lg hover:bg-red-200 transition" data-id="${person.id}">
                                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                                        <path fill-rule="evenodd" d="M9 2a1 1 0 00-.894.553L7.382 4H4a1 1 0 000 2v10a2 2 0 002 2h8a2 2 0 002-2V6a1 1 0 100-2h-3.382l-.724-1.447A1 1 0 0011 2H9zM7 8a1 1 0 012 0v6a1 1 0 11-2 0V8zm5-1a1 1 0 00-1 1v6a1 1 0 102 0V8a1 1 0 00-1-1z" clip-rule="evenodd" />
                                    </svg>
                                </button>
                            </div>
                        </td>
                    `;
                    
                    resultsTableBody.appendChild(row);
                });
                
                // Add event listeners to edit and delete buttons
                document.querySelectorAll('.edit-btn').forEach(button => {
                    button.addEventListener('click', () => {
                        const personId = button.getAttribute('data-id');
                        showEditPersonModal(personId);
                    });
                });
                
                document.querySelectorAll('.delete-btn').forEach(button => {
                    button.addEventListener('click', () => {
                        const personId = button.getAttribute('data-id');
                        showDeleteConfirmation(personId);
                    });
                });
            } else {
                noResults.classList.remove('hidden');
            }
        }
        
        // Get status badge HTML
        function getStatusBadge(status) {
            if (status === 'ยืนยันแล้ว') {
                return `<span class="inline-flex items-center px-3 py-1 rounded-full text-sm font-medium bg-green-100 text-green-800">
                    <svg class="w-4 h-4 mr-1.5" fill="currentColor" viewBox="0 0 20 20">
                        <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
                    </svg>
                    ยืนยันแล้ว
                </span>`;
            } else if (status === 'รอการยืนยัน') {
                return `<span class="inline-flex items-center px-3 py-1 rounded-full text-sm font-medium bg-yellow-100 text-yellow-800">
                    <svg class="w-4 h-4 mr-1.5" fill="currentColor" viewBox="0 0 20 20">
                        <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-12a1 1 0 10-2 0v4a1 1 0 00.293.707l2.828 2.829a1 1 0 101.415-1.415L11 9.586V6z" clip-rule="evenodd" />
                    </svg>
                    รอการยืนยัน
                </span>`;
            } else if (status === 'ยกเลิก') {
                return `<span class="inline-flex items-center px-3 py-1 rounded-full text-sm font-medium bg-red-100 text-red-800">
                    <svg class="w-4 h-4 mr-1.5" fill="currentColor" viewBox="0 0 20 20">
                        <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zM8.707 7.293a1 1 0 00-1.414 1.414L8.586 10l-1.293 1.293a1 1 0 101.414 1.414L10 11.414l1.293 1.293a1 1 0 001.414-1.414L11.414 10l1.293-1.293a1 1 0 00-1.414-1.414L10 8.586 8.707 7.293z" clip-rule="evenodd" />
                    </svg>
                    ยกเลิก
                </span>`;
            } else {
                return `<span class="inline-flex items-center px-3 py-1 rounded-full text-sm font-medium bg-gray-100 text-gray-800">
                    ${status || 'ไม่ระบุ'}
                </span>`;
            }
        }
        
        // Show add person modal
        function showAddPersonModal() {
            // Reset form
            personForm.reset();
            document.getElementById('personId').value = '';
            currentPersonId = null;
            
            // Update modal title and icon
            modalTitle.innerHTML = `
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 mr-2 text-green-500" viewBox="0 0 20 20" fill="currentColor">
                    <path fill-rule="evenodd" d="M10 3a1 1 0 011 1v5h5a1 1 0 110 2h-5v5a1 1 0 11-2 0v-5H4a1 1 0 110-2h5V4a1 1 0 011-1z" clip-rule="evenodd" />
                </svg>
                เพิ่มรายชื่อใหม่
            `;
            
            // Update save button
            saveButtonText.textContent = 'บันทึก';
            document.getElementById('savePersonBtn').classList.remove('from-blue-500', 'to-indigo-500', 'hover:from-blue-600', 'hover:to-indigo-600');
            document.getElementById('savePersonBtn').classList.add('from-green-500', 'to-emerald-500', 'hover:from-green-600', 'hover:to-emerald-600');
            
            // Show modal
            personModal.classList.remove('hidden');
        }
        
        // Show edit person modal
        function showEditPersonModal(personId) {
            showLoading();
            currentPersonId = personId;
            
            // Fetch person data using URLSearchParams
            fetch(`${API_URL}?action=getPerson&id=${personId}`)
                .then(response => response.json())
                .then(response => {
                    hideLoading();
                    
                    if (response.success && response.data) {
                        const person = response.data;
                        
                        // Fill form with person data
                        document.getElementById('personId').value = person.id;
                        document.getElementById('personPrefix').value = person.prefix || '';
                        document.getElementById('personFirstName').value = person.firstName || '';
                        document.getElementById('personLastName').value = person.lastName || '';
                        document.getElementById('personDepartment').value = person.department || '';
                        document.getElementById('personPosition').value = person.position || '';
                        document.getElementById('personStatus').value = person.status || '';
                        
                        // Update modal title and icon
                        modalTitle.innerHTML = `
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 mr-2 text-blue-500" viewBox="0 0 20 20" fill="currentColor">
                                <path d="M13.586 3.586a2 2 0 112.828 2.828l-.793.793-2.828-2.828.793-.793zM11.379 5.793L3 14.172V17h2.828l8.38-8.379-2.83-2.828z" />
                            </svg>
                            แก้ไขข้อมูล
                        `;
                        
                        // Update save button
                        saveButtonText.textContent = 'บันทึกการแก้ไข';
                        document.getElementById('savePersonBtn').classList.remove('from-green-500', 'to-emerald-500', 'hover:from-green-600', 'hover:to-emerald-600');
                        document.getElementById('savePersonBtn').classList.add('from-blue-500', 'to-indigo-500', 'hover:from-blue-600', 'hover:to-indigo-600');
                        
                        // Show modal
                        personModal.classList.remove('hidden');
                    } else {
                        showToast('ไม่พบข้อมูลที่ต้องการแก้ไข', 'error');
                    }
                })
                .catch(error => {
                    hideLoading();
                    console.error('Error:', error);
                    showToast('เกิดข้อผิดพลาดในการดึงข้อมูล', 'error');
                });
        }
        
        // Handle person form submit
        function handlePersonFormSubmit(e) {
            e.preventDefault();
            
            const personId = document.getElementById('personId').value;
            const prefix = document.getElementById('personPrefix').value;
            const firstName = document.getElementById('personFirstName').value;
            const lastName = document.getElementById('personLastName').value;
            const department = document.getElementById('personDepartment').value;
            const position = document.getElementById('personPosition').value;
            const status = document.getElementById('personStatus').value;
            
            // Show spinner in save button
            saveButtonText.textContent = personId ? 'กำลังบันทึก...' : 'กำลังเพิ่ม...';
            saveSpinner.classList.remove('hidden');
            
            // Using FormData for the request
            const formData = new FormData();
            formData.append('action', personId ? 'update' : 'add');
            if (personId) formData.append('id', personId);
            formData.append('prefix', prefix);
            formData.append('firstName', firstName);
            formData.append('lastName', lastName);
            formData.append('department', department);
            formData.append('position', position);
            formData.append('status', status);
            
            // Call API
            fetch(API_URL, {
                method: 'POST',
                body: formData
            })
            .then(response => response.json())
            .then(result => {
                // Hide spinner
                saveSpinner.classList.add('hidden');
                
                if (result.success) {
                    personModal.classList.add('hidden');
                    showToast(personId ? 'บันทึกการแก้ไขข้อมูลเรียบร้อยแล้ว' : 'เพิ่มข้อมูลเรียบร้อยแล้ว', 'success');
                    
                    // Refresh search results if we were searching
                    if (resultsContainer.classList.contains('hidden') === false) {
                        searchPeople();
                    }
                } else {
                    showToast(result.message || 'เกิดข้อผิดพลาดในการบันทึกข้อมูล', 'error');
                }
            })
            .catch(error => {
                // Hide spinner
                saveSpinner.classList.add('hidden');
                
                console.error('Error:', error);
                showToast('เกิดข้อผิดพลาดในการบันทึกข้อมูล', 'error');
            });
        }
        
        // Show delete confirmation
        function showDeleteConfirmation(personId) {
            currentPersonId = personId;
            confirmationModal.classList.remove('hidden');
        }
        
        // Confirm delete
        function confirmDelete() {
            if (!currentPersonId) return;
            
            // Show spinner in delete button
            document.getElementById('confirmDeleteBtn').querySelector('span').textContent = 'กำลังลบ...';
            deleteSpinner.classList.remove('hidden');
            
            // Using FormData for the request
            const formData = new FormData();
            formData.append('action', 'delete');
            formData.append('id', currentPersonId);
            
            // Call API
            fetch(API_URL, {
                method: 'POST',
                body: formData
            })
            .then(response => response.json())
            .then(result => {
                // Hide spinner
                deleteSpinner.classList.add('hidden');
                document.getElementById('confirmDeleteBtn').querySelector('span').textContent = 'ยืนยัน';
                
                confirmationModal.classList.add('hidden');
                
                if (result.success) {
                    showToast('ลบข้อมูลเรียบร้อยแล้ว', 'success');
                    
                    // Refresh search results
                    searchPeople();
                } else {
                    showToast(result.message || 'เกิดข้อผิดพลาดในการลบข้อมูล', 'error');
                }
            })
            .catch(error => {
                // Hide spinner
                deleteSpinner.classList.add('hidden');
                document.getElementById('confirmDeleteBtn').querySelector('span').textContent = 'ยืนยัน';
                
                confirmationModal.classList.add('hidden');
                console.error('Error:', error);
                showToast('เกิดข้อผิดพลาดในการลบข้อมูล', 'error');
            });
        }
        
        // Show loading indicator
        function showLoading() {
            loadingIndicator.classList.remove('hidden');
        }
        
        // Hide loading indicator
        function hideLoading() {
            loadingIndicator.classList.add('hidden');
        }
        
        // Show toast notification
        function showToast(message, type = 'success') {
            const toast = document.getElementById('toast');
            const toastMessage = document.getElementById('toastMessage');
            
            // Set message and style based on type
            if (type === 'success') {
                toast.className = 'fixed bottom-4 right-4 px-6 py-3 rounded-lg shadow-lg z-50 bg-green-100 text-green-800 toast';
                toastMessage.innerHTML = `
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mr-2" viewBox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
                    </svg>
                    ${message}
                `;
            } else {
                toast.className = 'fixed bottom-4 right-4 px-6 py-3 rounded-lg shadow-lg z-50 bg-red-100 text-red-800 toast';
                toastMessage.innerHTML = `
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mr-2" viewBox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zM8.707 7.293a1 1 0 00-1.414 1.414L8.586 10l-1.293 1.293a1 1 0 101.414 1.414L10 11.414l1.293 1.293a1 1 0 001.414-1.414L11.414 10l1.293-1.293a1 1 0 00-1.414-1.414L10 8.586 8.707 7.293z" clip-rule="evenodd" />
                    </svg>
                    ${message}
                `;
            }
            
            // Show toast
            toast.classList.remove('hidden');
            
            // Hide toast after 3 seconds
            setTimeout(() => {
                toast.classList.add('hidden');
            }, 3000);
        }
    </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'94c5039713d65f57',t:'MTc0OTM1MDMxNi4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>

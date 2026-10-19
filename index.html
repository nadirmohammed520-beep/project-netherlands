<!DOCTYPE html>
<html lang="en" class="h-full bg-slate-950 text-slate-100">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Productivity & Study Hub</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Lucide Icons -->
    <script src="https://unpkg.com/lucide@latest"></script>
    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    colors: {
                        brand: {
                            50: '#f0f9ff',
                            100: '#e0f2fe',
                            500: '#0ea5e9',
                            600: '#0284c7',
                            700: '#0369a1',
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Inter', sans-serif; }
        ::-webkit-scrollbar { width: 6px; height: 6px; }
        ::-webkit-scrollbar-track { background: #0f172a; }
        ::-webkit-scrollbar-thumb { background: #334155; border-radius: 4px; }
    </style>
</head>
<body class="h-full flex flex-col md:flex-row overflow-hidden bg-slate-950 text-slate-100 selection:bg-sky-500 selection:text-white">

    <!-- Navigation Sidebar -->
    <aside class="w-full md:w-64 bg-slate-900 border-r border-slate-800 flex flex-col justify-between shrink-0">
        <div>
            <!-- Logo & Header -->
            <div class="p-5 border-b border-slate-800 flex items-center justify-between">
                <div class="flex items-center space-x-3">
                    <div class="p-2 bg-sky-600 text-white rounded-xl shadow-lg shadow-sky-500/30">
                        <i data-lucide="graduation-cap" class="w-6 h-6"></i>
                    </div>
                    <div>
                        <h1 class="font-extrabold text-base text-white tracking-tight leading-none">STUDY HUB</h1>
                        <span class="text-xs text-sky-400 font-medium">Student Dashboard</span>
                    </div>
                </div>
            </div>

            <!-- Navigation Links -->
            <nav class="p-4 space-y-1">
                <button onclick="switchTab('dashboard')" id="nav-dashboard" class="w-full flex items-center space-x-3 px-4 py-3 rounded-xl font-semibold text-sm transition-all bg-sky-600 text-white shadow-lg shadow-sky-600/20">
                    <i data-lucide="layout-dashboard" class="w-5 h-5"></i>
                    <span>Dashboard</span>
                </button>
                <button onclick="switchTab('tasks')" id="nav-tasks" class="w-full flex items-center space-x-3 px-4 py-3 rounded-xl font-medium text-sm text-slate-400 hover:text-white hover:bg-slate-800/60 transition-all">
                    <i data-lucide="check-square" class="w-5 h-5"></i>
                    <span>Assignment Planner</span>
                </button>
                <button onclick="switchTab('notes')" id="nav-notes" class="w-full flex items-center space-x-3 px-4 py-3 rounded-xl font-medium text-sm text-slate-400 hover:text-white hover:bg-slate-800/60 transition-all">
                    <i data-lucide="file-text" class="w-5 h-5"></i>
                    <span>Notebooks & Notes</span>
                </button>
                <button onclick="switchTab('timer')" id="nav-timer" class="w-full flex items-center space-x-3 px-4 py-3 rounded-xl font-medium text-sm text-slate-400 hover:text-white hover:bg-slate-800/60 transition-all">
                    <i data-lucide="timer" class="w-5 h-5"></i>
                    <span>Pomodoro Timer</span>
                </button>
            </nav>
        </div>

        <!-- Quick Stats Banner at bottom of sidebar -->
        <div class="p-4 m-4 rounded-2xl bg-slate-950 border border-slate-800">
            <div class="flex items-center justify-between text-xs text-slate-400 mb-2">
                <span>Daily Focus Target</span>
                <span id="sidebar-focus-percent" class="font-bold text-sky-400">0%</span>
            </div>
            <div class="w-full bg-slate-800 h-2 rounded-full overflow-hidden">
                <div id="sidebar-progress-bar" class="bg-sky-500 h-full w-0 transition-all duration-500"></div>
            </div>
        </div>
    </aside>

    <!-- Main Content Viewport -->
    <main class="flex-1 overflow-y-auto p-4 sm:p-8 bg-slate-950">
        
        <!-- DASHBOARD TAB -->
        <section id="tab-dashboard" class="space-y-8 max-w-7xl mx-auto">
            <header class="flex flex-col sm:flex-row sm:items-center justify-between gap-4 border-b border-slate-800 pb-6">
                <div>
                    <h2 class="text-2xl sm:text-3xl font-black text-white tracking-tight">Welcome Back! 👋</h2>
                    <p class="text-sm text-slate-400">Here is a quick breakdown of your study progress and upcoming tasks.</p>
                </div>
                <button onclick="switchTab('tasks')" class="bg-sky-600 hover:bg-sky-500 text-white px-4 py-2.5 rounded-xl font-semibold text-sm shadow-lg shadow-sky-600/20 transition-all flex items-center gap-2 self-start sm:self-auto">
                    <i data-lucide="plus" class="w-4 h-4"></i> Add New Task
                </button>
            </header>

            <!-- Metrics Overview Grid -->
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
                <div class="bg-slate-900 border border-slate-800 p-5 rounded-2xl flex items-center justify-between">
                    <div>
                        <span class="text-xs font-bold text-slate-400 uppercase tracking-wider">Pending Tasks</span>
                        <div id="dash-pending-count" class="text-3xl font-black text-white mt-1">0</div>
                    </div>
                    <div class="p-3 bg-amber-500/10 text-amber-400 rounded-xl">
                        <i data-lucide="clock" class="w-6 h-6"></i>
                    </div>
                </div>

                <div class="bg-slate-900 border border-slate-800 p-5 rounded-2xl flex items-center justify-between">
                    <div>
                        <span class="text-xs font-bold text-slate-400 uppercase tracking-wider">Completed Tasks</span>
                        <div id="dash-completed-count" class="text-3xl font-black text-white mt-1">0</div>
                    </div>
                    <div class="p-3 bg-emerald-500/10 text-emerald-400 rounded-xl">
                        <i data-lucide="check-circle-2" class="w-6 h-6"></i>
                    </div>
                </div>

                <div class="bg-slate-900 border border-slate-800 p-5 rounded-2xl flex items-center justify-between">
                    <div>
                        <span class="text-xs font-bold text-slate-400 uppercase tracking-wider">Focus Sessions</span>
                        <div id="dash-session-count" class="text-3xl font-black text-white mt-1">0</div>
                    </div>
                    <div class="p-3 bg-sky-500/10 text-sky-400 rounded-xl">
                        <i data-lucide="flame" class="w-6 h-6"></i>
                    </div>
                </div>

                <div class="bg-slate-900 border border-slate-800 p-5 rounded-2xl flex items-center justify-between">
                    <div>
                        <span class="text-xs font-bold text-slate-400 uppercase tracking-wider">Notebooks</span>
                        <div id="dash-note-count" class="text-3xl font-black text-white mt-1">0</div>
                    </div>
                    <div class="p-3 bg-purple-500/10 text-purple-400 rounded-xl">
                        <i data-lucide="book-open" class="w-6 h-6"></i>
                    </div>
                </div>
            </div>

            <!-- Urgent Assignments Preview -->
            <div class="bg-slate-900 border border-slate-800 rounded-2xl p-6">
                <div class="flex items-center justify-between mb-4">
                    <h3 class="font-bold text-lg text-white flex items-center gap-2">
                        <i data-lucide="alert-circle" class="w-5 h-5 text-sky-400"></i> Upcoming Deadlines
                    </h3>
                    <button onclick="switchTab('tasks')" class="text-xs font-semibold text-sky-400 hover:text-sky-300">View All Tasks &rarr;</button>
                </div>
                <div id="dash-urgent-list" class="space-y-3">
                    <!-- JavaScript rendered dynamic items -->
                </div>
            </div>
        </section>

        <!-- ASSIGNMENT PLANNER TAB -->
        <section id="tab-tasks" class="space-y-6 max-w-7xl mx-auto hidden">
            <header class="flex flex-col sm:flex-row sm:items-center justify-between gap-4 border-b border-slate-800 pb-6">
                <div>
                    <h2 class="text-2xl sm:text-3xl font-black text-white tracking-tight">Assignment Planner</h2>
                    <p class="text-sm text-slate-400">Track homework, school projects, exams, and personal study goals.</p>
                </div>
                <button onclick="toggleModal('task-modal', true)" class="bg-sky-600 hover:bg-sky-500 text-white px-4 py-2.5 rounded-xl font-semibold text-sm shadow-lg shadow-sky-600/20 transition-all flex items-center gap-2">
                    <i data-lucide="plus-circle" class="w-4 h-4"></i> New Task
                </button>
            </header>

            <!-- Task Filters -->
            <div class="flex flex-wrap items-center justify-between gap-4 bg-slate-900 p-4 rounded-2xl border border-slate-800">
                <div class="flex items-center space-x-2">
                    <button onclick="filterTasks('all')" id="filter-all" class="px-3 py-1.5 rounded-lg text-xs font-bold bg-sky-600 text-white">All Tasks</button>
                    <button onclick="filterTasks('pending')" id="filter-pending" class="px-3 py-1.5 rounded-lg text-xs font-semibold text-slate-400 hover:bg-slate-800">Pending</button>
                    <button onclick="filterTasks('completed')" id="filter-completed" class="px-3 py-1.5 rounded-lg text-xs font-semibold text-slate-400 hover:bg-slate-800">Completed</button>
                </div>
            </div>

            <!-- Task List Container -->
            <div id="tasks-container" class="space-y-3">
                <!-- Javascript populated tasks -->
            </div>
        </section>

        <!-- NOTES TAB -->
        <section id="tab-notes" class="space-y-6 max-w-7xl mx-auto hidden">
            <header class="flex flex-col sm:flex-row sm:items-center justify-between gap-4 border-b border-slate-800 pb-6">
                <div>
                    <h2 class="text-2xl sm:text-3xl font-black text-white tracking-tight">Notebooks & Study Notes</h2>
                    <p class="text-sm text-slate-400">Keep class summaries, research notes, and study guides organized.</p>
                </div>
                <button onclick="toggleModal('note-modal', true)" class="bg-purple-600 hover:bg-purple-500 text-white px-4 py-2.5 rounded-xl font-semibold text-sm shadow-lg shadow-purple-600/20 transition-all flex items-center gap-2">
                    <i data-lucide="pen-tool" class="w-4 h-4"></i> Create Note
                </button>
            </header>

            <!-- Notes Grid -->
            <div id="notes-container" class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4">
                <!-- Javascript populated notes -->
            </div>
        </section>

        <!-- POMODORO TIMER TAB -->
        <section id="tab-timer" class="space-y-8 max-w-3xl mx-auto hidden">
            <header class="text-center border-b border-slate-800 pb-6">
                <h2 class="text-2xl sm:text-3xl font-black text-white tracking-tight">Pomodoro Focus Timer</h2>
                <p class="text-sm text-slate-400 mt-1">Focus intensely for 25 minutes, then take a short 5-minute break to stay sharp.</p>
            </header>

            <div class="bg-slate-900 border border-slate-800 rounded-3xl p-8 sm:p-12 text-center shadow-2xl relative overflow-hidden">
                <!-- Session Badge -->
                <div class="inline-flex items-center gap-2 px-4 py-1.5 rounded-full bg-sky-500/10 border border-sky-500/30 text-sky-400 text-xs font-bold uppercase tracking-widest mb-8">
                    <i data-lucide="flame" class="w-4 h-4"></i> <span id="timer-mode-label">Work Session</span>
                </div>

                <!-- Circular Clock Display -->
                <div class="text-6xl sm:text-8xl font-black text-white tracking-tighter my-4 font-mono">
                    <span id="timer-display">25:00</span>
                </div>

                <!-- Timer Controls -->
                <div class="flex items-center justify-center gap-4 mt-8">
                    <button id="timer-start-btn" onclick="toggleTimer()" class="bg-sky-600 hover:bg-sky-500 text-white px-8 py-4 rounded-2xl font-bold text-lg shadow-xl shadow-sky-600/30 transition-all flex items-center gap-3">
                        <i data-lucide="play" class="w-5 h-5"></i> Start Focus
                    </button>
                    <button onclick="resetTimer()" class="bg-slate-800 hover:bg-slate-700 text-slate-300 p-4 rounded-2xl font-semibold transition-all border border-slate-700">
                        <i data-lucide="rotate-ccw" class="w-5 h-5"></i>
                    </button>
                </div>

                <!-- Session Counter -->
                <div class="mt-8 pt-8 border-t border-slate-800/80 flex justify-center items-center gap-6 text-slate-400 text-xs font-medium">
                    <div>Completed Today: <strong id="completed-sessions-count" class="text-white text-sm ml-1">0</strong></div>
                </div>
            </div>
        </section>

    </main>

    <!-- NEW TASK MODAL -->
    <div id="task-modal" class="fixed inset-0 bg-slate-950/80 backdrop-blur-sm z-50 hidden flex items-center justify-center p-4">
        <div class="bg-slate-900 border border-slate-800 rounded-2xl max-w-md w-full p-6 shadow-2xl space-y-4">
            <div class="flex items-center justify-between border-b border-slate-800 pb-3">
                <h3 class="font-bold text-lg text-white">Create New Assignment</h3>
                <button onclick="toggleModal('task-modal', false)" class="text-slate-400 hover:text-white"><i data-lucide="x" class="w-5 h-5"></i></button>
            </div>
            <form onsubmit="handleAddTask(event)" class="space-y-4">
                <div>
                    <label class="block text-xs font-bold text-slate-400 uppercase mb-1">Title</label>
                    <input id="task-title" type="text" required placeholder="e.g., History Essay Outline" class="w-full bg-slate-950 border border-slate-800 rounded-xl px-4 py-2.5 text-sm text-white focus:outline-none focus:border-sky-500">
                </div>
                <div class="grid grid-cols-2 gap-3">
                    <div>
                        <label class="block text-xs font-bold text-slate-400 uppercase mb-1">Subject / Tag</label>
                        <input id="task-tag" type="text" placeholder="History, Math, Science" class="w-full bg-slate-950 border border-slate-800 rounded-xl px-4 py-2.5 text-sm text-white focus:outline-none focus:border-sky-500">
                    </div>
                    <div>
                        <label class="block text-xs font-bold text-slate-400 uppercase mb-1">Due Date</label>
                        <input id="task-date" type="date" required class="w-full bg-slate-950 border border-slate-800 rounded-xl px-4 py-2.5 text-sm text-white focus:outline-none focus:border-sky-500">
                    </div>
                </div>
                <div class="flex justify-end gap-3 pt-2">
                    <button type="button" onclick="toggleModal('task-modal', false)" class="px-4 py-2 rounded-xl text-xs font-semibold text-slate-400 hover:bg-slate-800">Cancel</button>
                    <button type="submit" class="bg-sky-600 hover:bg-sky-500 text-white px-5 py-2 rounded-xl text-xs font-bold shadow-lg shadow-sky-600/20">Save Task</button>
                </div>
            </form>
        </div>
    </div>

    <!-- NEW NOTE MODAL -->
    <div id="note-modal" class="fixed inset-0 bg-slate-950/80 backdrop-blur-sm z-50 hidden flex items-center justify-center p-4">
        <div class="bg-slate-900 border border-slate-800 rounded-2xl max-w-lg w-full p-6 shadow-2xl space-y-4">
            <div class="flex items-center justify-between border-b border-slate-800 pb-3">
                <h3 class="font-bold text-lg text-white">Create Study Note</h3>
                <button onclick="toggleModal('note-modal', false)" class="text-slate-400 hover:text-white"><i data-lucide="x" class="w-5 h-5"></i></button>
            </div>
            <form onsubmit="handleAddNote(event)" class="space-y-4">
                <div>
                    <label class="block text-xs font-bold text-slate-400 uppercase mb-1">Note Title</label>
                    <input id="note-title" type="text" required placeholder="e.g., Biology Chapter 4 Summary" class="w-full bg-slate-950 border border-slate-800 rounded-xl px-4 py-2.5 text-sm text-white focus:outline-none focus:border-purple-500">
                </div>
                <div>
                    <label class="block text-xs font-bold text-slate-400 uppercase mb-1">Folder / Subject</label>
                    <input id="note-folder" type="text" placeholder="Biology" class="w-full bg-slate-950 border border-slate-800 rounded-xl px-4 py-2.5 text-sm text-white focus:outline-none focus:border-purple-500">
                </div>
                <div>
                    <label class="block text-xs font-bold text-slate-400 uppercase mb-1">Content</label>
                    <textarea id="note-content" rows="4" required placeholder="Write down key takeaways, study points..." class="w-full bg-slate-950 border border-slate-800 rounded-xl px-4 py-2.5 text-sm text-white focus:outline-none focus:border-purple-500"></textarea>
                </div>
                <div class="flex justify-end gap-3 pt-2">
                    <button type="button" onclick="toggleModal('note-modal', false)" class="px-4 py-2 rounded-xl text-xs font-semibold text-slate-400 hover:bg-slate-800">Cancel</button>
                    <button type="submit" class="bg-purple-600 hover:bg-purple-500 text-white px-5 py-2 rounded-xl text-xs font-bold shadow-lg shadow-purple-600/20">Save Note</button>
                </div>
            </form>
        </div>
    </div>

    <!-- Application JavaScript Logic -->
    <script>
        // Initial state
        let tasks = JSON.parse(localStorage.getItem('student_tasks')) || [
            { id: 1, title: 'Read History Chapter 5', tag: 'History', date: '2026-10-25', completed: false },
            { id: 2, title: 'Math Problem Set #3', tag: 'Math', date: '2026-10-22', completed: true }
        ];

        let notes = JSON.parse(localStorage.getItem('student_notes')) || [
            { id: 1, title: 'Civil Rights Movement Summary', folder: 'History', content: 'Key events, figures, and historical timeline overview.' }
        ];

        let timerState = {
            minutes: 25,
            seconds: 0,
            isRunning: false,
            interval: null,
            mode: 'work', // 'work' or 'break'
            sessionsCompleted: 0
        };

        let currentTaskFilter = 'all';

        // Tab Switcher
        function switchTab(tabId) {
            ['dashboard', 'tasks', 'notes', 'timer'].forEach(tab => {
                document.getElementById(`tab-${tab}`).classList.add('hidden');
                const navBtn = document.getElementById(`nav-${tab}`);
                if (navBtn) {
                    navBtn.className = "w-full flex items-center space-x-3 px-4 py-3 rounded-xl font-medium text-sm text-slate-400 hover:text-white hover:bg-slate-800/60 transition-all";
                }
            });

            document.getElementById(`tab-${tabId}`).classList.remove('hidden');
            const activeNav = document.getElementById(`nav-${tabId}`);
            if (activeNav) {
                activeNav.className = "w-full flex items-center space-x-3 px-4 py-3 rounded-xl font-semibold text-sm transition-all bg-sky-600 text-white shadow-lg shadow-sky-600/20";
            }

            renderAll();
        }

        // Render Application Data
        function renderAll() {
            renderDashboard();
            renderTasks();
            renderNotes();
            lucide.createIcons();
        }

        function renderDashboard() {
            const pending = tasks.filter(t => !t.completed);
            const completed = tasks.filter(t => t.completed);

            document.getElementById('dash-pending-count').innerText = pending.length;
            document.getElementById('dash-completed-count').innerText = completed.length;
            document.getElementById('dash-session-count').innerText = timerState.sessionsCompleted;
            document.getElementById('dash-note-count').innerText = notes.length;

            const percent = tasks.length ? Math.round((completed.length / tasks.length) * 100) : 0;
            document.getElementById('sidebar-focus-percent').innerText = `${percent}%`;
            document.getElementById('sidebar-progress-bar').style.width = `${percent}%`;

            const urgentContainer = document.getElementById('dash-urgent-list');
            if (pending.length === 0) {
                urgentContainer.innerHTML = `<p class="text-xs text-slate-500 py-2">No pending assignments!</p>`;
            } else {
                urgentContainer.innerHTML = pending.slice(0, 3).map(task => `
                    <div class="flex items-center justify-between bg-slate-950 p-3 rounded-xl border border-slate-800/80">
                        <div class="flex items-center space-x-3">
                            <button onclick="toggleTask(${task.id})" class="text-slate-600 hover:text-sky-400">
                                <i data-lucide="circle" class="w-4 h-4"></i>
                            </button>
                            <div>
                                <span class="text-xs font-semibold text-white block">${task.title}</span>
                                <span class="text-[10px] text-slate-400">${task.tag || 'General'}</span>
                            </div>
                        </div>
                        <span class="text-xs font-bold text-sky-400 px-2 py-1 bg-sky-500/10 rounded-lg">Due: ${task.date}</span>
                    </div>
                `).join('');
            }
        }

        function renderTasks() {
            const container = document.getElementById('tasks-container');
            let filtered = tasks;
            if (currentTaskFilter === 'pending') filtered = tasks.filter(t => !t.completed);
            if (currentTaskFilter === 'completed') filtered = tasks.filter(t => t.completed);

            if (filtered.length === 0) {
                container.innerHTML = `<p class="text-center text-slate-500 py-8 text-sm">No assignments found.</p>`;
                return;
            }

            container.innerHTML = filtered.map(task => `
                <div class="flex items-center justify-between bg-slate-900 border border-slate-800 p-4 rounded-2xl">
                    <div class="flex items-center space-x-3">
                        <button onclick="toggleTask(${task.id})" class="${task.completed ? 'text-emerald-400' : 'text-slate-500 hover:text-sky-400'}">
                            <i data-lucide="${task.completed ? 'check-circle-2' : 'circle'}" class="w-5 h-5"></i>
                        </button>
                        <div>
                            <span class="text-sm font-semibold text-white ${task.completed ? 'line-through text-slate-500' : ''}">${task.title}</span>
                            <div class="flex items-center space-x-2 mt-0.5">
                                <span class="text-[10px] font-bold text-sky-400 px-2 py-0.5 bg-sky-500/10 rounded-md">${task.tag || 'General'}</span>
                                <span class="text-xs text-slate-500">Due: ${task.date}</span>
                            </div>
                        </div>
                    </div>
                    <button onclick="deleteTask(${task.id})" class="text-slate-500 hover:text-red-400 p-2">
                        <i data-lucide="trash-2" class="w-4 h-4"></i>
                    </button>
                </div>
            `).join('');
        }

        function renderNotes() {
            const container = document.getElementById('notes-container');
            if (notes.length === 0) {
                container.innerHTML = `<p class="text-center text-slate-500 py-8 text-sm col-span-full">No study notes yet.</p>`;
                return;
            }

            container.innerHTML = notes.map(note => `
                <div class="bg-slate-900 border border-slate-800 p-5 rounded-2xl flex flex-col justify-between space-y-4">
                    <div>
                        <div class="flex items-center justify-between mb-2">
                            <span class="text-[10px] font-bold text-purple-400 px-2 py-0.5 bg-purple-500/10 rounded-md">${note.folder || 'Notes'}</span>
                            <button onclick="deleteNote(${note.id})" class="text-slate-500 hover:text-red-400">
                                <i data-lucide="trash" class="w-3.5 h-3.5"></i>
                            </button>
                        </div>
                        <h4 class="font-bold text-white text-base mb-1">${note.title}</h4>
                        <p class="text-xs text-slate-400 leading-relaxed">${note.content}</p>
                    </div>
                </div>
            `).join('');
        }

        // Action Handlers
        function handleAddTask(e) {
            e.preventDefault();
            const title = document.getElementById('task-title').value;
            const tag = document.getElementById('task-tag').value;
            const date = document.getElementById('task-date').value;

            tasks.push({ id: Date.now(), title, tag, date, completed: false });
            localStorage.setItem('student_tasks', JSON.stringify(tasks));
            
            toggleModal('task-modal', false);
            e.target.reset();
            renderAll();
        }

        function handleAddNote(e) {
            e.preventDefault();
            const title = document.getElementById('note-title').value;
            const folder = document.getElementById('note-folder').value;
            const content = document.getElementById('note-content').value;

            notes.push({ id: Date.now(), title, folder, content });
            localStorage.setItem('student_notes', JSON.stringify(notes));

            toggleModal('note-modal', false);
            e.target.reset();
            renderAll();
        }

        function toggleTask(id) {
            tasks = tasks.map(t => t.id === id ? { ...t, completed: !t.completed } : t);
            localStorage.setItem('student_tasks', JSON.stringify(tasks));
            renderAll();
        }

        function deleteTask(id) {
            tasks = tasks.filter(t => t.id !== id);
            localStorage.setItem('student_tasks', JSON.stringify(tasks));
            renderAll();
        }

        function deleteNote(id) {
            notes = notes.filter(n => n.id !== id);
            localStorage.setItem('student_notes', JSON.stringify(notes));
            renderAll();
        }

        function filterTasks(filter) {
            currentTaskFilter = filter;
            ['all', 'pending', 'completed'].forEach(f => {
                const btn = document.getElementById(`filter-${f}`);
                if (f === filter) {
                    btn.className = "px-3 py-1.5 rounded-lg text-xs font-bold bg-sky-600 text-white";
                } else {
                    btn.className = "px-3 py-1.5 rounded-lg text-xs font-semibold text-slate-400 hover:bg-slate-800";
                }
            });
            renderTasks();
            lucide.createIcons();
        }

        function toggleModal(modalId, show) {
            document.getElementById(modalId).classList.toggle('hidden', !show);
        }

        // Pomodoro Timer
        function updateTimerDisplay() {
            const mins = String(timerState.minutes).padStart(2, '0');
            const secs = String(timerState.seconds).padStart(2, '0');
            document.getElementById('timer-display').innerText = `${mins}:${secs}`;
        }

        function toggleTimer() {
            const btn = document.getElementById('timer-start-btn');
            if (timerState.isRunning) {
                clearInterval(timerState.interval);
                timerState.isRunning = false;
                btn.innerHTML = `<i data-lucide="play" class="w-5 h-5"></i> Start Focus`;
            } else {
                timerState.isRunning = true;
                btn.innerHTML = `<i data-lucide="pause" class="w-5 h-5"></i> Pause`;
                timerState.interval = setInterval(() => {
                    if (timerState.seconds === 0) {
                        if (timerState.minutes === 0) {
                            clearInterval(timerState.interval);
                            timerState.isRunning = false;
                            if (timerState.mode === 'work') {
                                timerState.sessionsCompleted++;
                                timerState.mode = 'break';
                                timerState.minutes = 5;
                                document.getElementById('timer-mode-label').innerText = 'Short Break';
                            } else {
                                timerState.mode = 'work';
                                timerState.minutes = 25;
                                document.getElementById('timer-mode-label').innerText = 'Work Session';
                            }
                            document.getElementById('completed-sessions-count').innerText = timerState.sessionsCompleted;
                            btn.innerHTML = `<i data-lucide="play" class="w-5 h-5"></i> Start Focus`;
                            renderAll();
                        } else {
                            timerState.minutes--;
                            timerState.seconds = 59;
                        }
                    } else {
                        timerState.seconds--;
                    }
                    updateTimerDisplay();
                }, 1000);
            }
            lucide.createIcons();
        }

        function resetTimer() {
            clearInterval(timerState.interval);
            timerState.isRunning = false;
            timerState.minutes = timerState.mode === 'work' ? 25 : 5;
            timerState.seconds = 0;
            document.getElementById('timer-start-btn').innerHTML = `<i data-lucide="play" class="w-5 h-5"></i> Start Focus`;
            updateTimerDisplay();
            lucide.createIcons();
        }

        // Initialize App on Load
        window.onload = function() {
            renderAll();
        };
    </script>
</body>
</html>

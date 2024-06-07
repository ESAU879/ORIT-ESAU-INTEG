<script setup>
import AuthenticatedLayout from '@/Layouts/AuthenticatedLayout.vue';
import { Head } from '@inertiajs/vue3';
</script>

<template>
    <Head title="Dashboard" />

    <div class="topbar">
            <!-- Logo -->
            <div class="topbar-logo">
                <img src="/images/logo.png" alt="Example Image" style="max-width: 100%; height: 150px;" />
            </div>
            <!-- Navigation Links -->
            <nav class="topbar-nav">
                <!-- Navigation Links Here -->
            </nav>
        </div>
    
    <AuthenticatedLayout>
        
        <aside id="sidebar" class="sidebar">
            <ul class="nav flex-column">
                <li class="nav-item">
                    <a class="nav-link" href="pages-register.html">
                        <i class="bi bi-card-list"></i>
                        <span>Dashboard</span>
                    </a>
                </li>

                <li class="nav-item">
                    <a class="nav-link" href="pages-register.html">
                        <i class="bi bi-card-list"></i>
                        <span>Tenants Profile</span>
                    </a>
                </li>

                <li class="nav-item">
                    <a class="nav-link" href="index.html">
                        <i class="bi bi-grid"></i>
                        <span>Room Management</span>
                    </a>
                </li>

                <li class="nav-item">
                    <a class="nav-link" href="index.html">
                        <i class="bi bi-grid"></i>
                        <span>Bed Management</span>
                    </a>
                </li>

                <li class="nav-item">
                    <a class="nav-link" href="index.html">
                        <i class="bi bi-grid"></i>
                        <span>Utility Bills</span>
                    </a>
                </li>

                <li class="nav-item">
                    <a class="nav-link" href="index.html">
                        <i class="bi bi-grid"></i>
                        <span>Payment History</span>
                    </a>
                </li>

                <li class="nav-item">
                    <a class="nav-link" href="index.html">
                        <i class="bi bi-grid"></i>
                        <span>SMS Configuration</span>
                    </a>
                </li>

            </ul>
        </aside>
    </AuthenticatedLayout>
</template>

<style scoped>
.sidebar {
    width: 350px;
    line-height: 60px;
    background-color: #f8f9fa;
    padding: 50px;
    border-right: 0.5px solid #dee2e6;
}

.nav-link {
    display: flex;
    align-items: center;
    color: #212529;
    text-decoration: none;
    padding: 10px 0;
}

.nav-link:hover {
    background-color: #e9ecef;
}

.nav-link i {
    margin-right: 10px;
}


</style>
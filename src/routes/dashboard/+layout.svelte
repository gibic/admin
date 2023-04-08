<script lang="ts">
    import Sidebar from "../../lib/components/Sidebar.svelte";
    import Header from "../../lib/components/Header.svelte";
    import '../../lib/styles.css';
</script>
<div class="bg-gray-100">
    <div class="container max-w-[1400px] mx-auto flex">
        <section class="sidebar h-screen w-[240px] py-2 border-r mr-7">
            <Sidebar />
        </section>
        <section class="flex grow flex-col py-2">
            <Header />
            <main>
                <!-- +page.svelte is rendered in this <slot> -->  
                <slot />
            </main>
        </section>
    </div>
</div>
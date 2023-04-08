<script lang="ts">
    import Search from "./Search.svelte";
    import Notifications from "./Notifications.svelte";
    import Avatar from "../ToyFaces.png";
</script>

<header class="w-full mb-12 flex justify-between items-center">
    <section>
        <h1 class="font-bold text-4xl mt-3 text-purple-950">Dashboard</h1>
        <p class="text-gray-700 text-sm">Hi Admin, welcome back!</p>
    </section>
    <section>
        <div class="flex items-center">
            <Search />
            <Notifications />
            <div class="border-l pl-6 ml-6">
                <img src={Avatar} alt="Avatar" class="w-10 h-10 rounded-full"/>
            </div>
        </div>
    </section>
</header>
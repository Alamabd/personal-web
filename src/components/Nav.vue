
<template>
    <nav class="navbar bg-base-100 dark:bg-black">
        <div class="flex-1">
            <a href="." class="text-xl font-semibold">Alamabd</a>
        </div>
        <div class="flex-none">
            <ul class="menu menu-horizontal px-1">
                <li>
                    <a href="#">about</a>
                </li>
                <li class="relative">
                    <details>
                        <summary>
                            more
                        </summary>
                        <ul class="absolute z-10 right-0 p-2 bg-base-100 rounded-t-none">
                            <li>
                                <a class="text-nowrap">tech stack</a>
                            </li>
                            <li>
                                <a>Project</a>
                            </li>
                            <li>
                                <label class="flex cursor-pointer gap-2 sm:hidden">
                                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="5"/><path d="M12 1v2M12 21v2M4.2 4.2l1.4 1.4M18.4 18.4l1.4 1.4M1 12h2M21 12h2M4.2 19.8l1.4-1.4M18.4 5.6l1.4-1.4"/></svg>
                                    <input type="checkbox" value="synthwave" class="toggle theme-controller"/>
                                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 12.79A9 9 0 1 1 11.21 3 7 7 0 0 0 21 12.79z"></path></svg>
                                </label>
                            </li>
                        </ul>
                    </details>
                </li>
            </ul>
            <label class="ml-8 flex cursor-pointer gap-2 max-sm:hidden">
                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="5"/><path d="M12 1v2M12 21v2M4.2 4.2l1.4 1.4M18.4 18.4l1.4 1.4M1 12h2M21 12h2M4.2 19.8l1.4-1.4M18.4 5.6l1.4-1.4"/></svg>
                <input type="checkbox" value="synthwave" class="toggle theme-controller"/>
                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 12.79A9 9 0 1 1 11.21 3 7 7 0 0 0 21 12.79z"></path></svg>
            </label>
        </div>
    </nav>
</template>

<style scoped>
</style>
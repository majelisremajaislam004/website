<template>
    <main>
        <div>
            <navbar/>
        </div>
        <div class="container text-center" style="margin-top: 9rem;">
            <div>
                <h1>Periode 2021/2022</h1>
            </div>
        </div>
        <div class="row justify-content-center" style="margin-top: 2rem; margin-bottom: 2rem;">
            <div class="btn-group" role="group" aria-label="Basic mixed styles example">
            <button type="button" class="btn btn-primary"><NuxtLink class="a text-white" style="text-decoration: none;" to="/about1">2019/2020</NuxtLink></button>
            <button type="button" class="btn btn-success"><NuxtLink class="a text-white" style="text-decoration: none;" to="/about">2020/2021</NuxtLink></button>
            <button type="button" class="btn btn-warning"><NuxtLink class="a text-white" style="text-decoration: none;" to="/about2">2021/2022</NuxtLink></button>
            </div>
        </div>
        <div>
            <end/>
        </div>
    </main>
</template>

<!--
  PharmaOS Homepage
  Mini Health Hub landing page for Sharma Medical Store.
-->

<svelte:head>
  <title>PharmaOS - Sharma Medical Store</title>
  <meta
    name="description"
    content="Sharma Medical Store ka Mini Health Hub - VIP Health Pass, NABL Lab Test aur Health Vault."
  />
</svelte:head>

<section class="min-h-screen bg-slate-50 px-4 py-12 sm:px-6 lg:px-8">
  <div class="mx-auto max-w-6xl">

    <!-- Header -->
    <div class="text-center">
      <div class="mb-4 inline-flex rounded-full bg-green-100 px-4 py-2 text-sm font-semibold text-green-700">
        PharmaOS · Mini Health Hub
      </div>

      <h1 class="text-3xl font-extrabold tracking-tight text-slate-900 sm:text-5xl">
        PharmaOS - Aapka Medical Store,
        <span class="text-blue-700"> Ab Mini Health Hub</span>
      </h1>

      <p class="mt-4 text-lg font-medium text-slate-500">
        Sharma Medical Store - Jamshedpur
      </p>

      <p class="mx-auto mt-4 max-w-2xl text-slate-600">
        Dawai se lekar lab test aur health reports tak,
        aapki sehat ki zaroorat ab ek hi jagah.
      </p>
    </div>

    <!-- Health Service Cards -->
    <div class="mt-12 grid grid-cols-1 gap-6 md:grid-cols-3">

      <!-- VIP Health Pass -->
      <div class="rounded-2xl border border-blue-100 bg-white p-6 shadow-sm transition hover:shadow-md">
        <div class="mb-4 flex h-12 w-12 items-center justify-center rounded-xl bg-blue-100 text-2xl">
          💙
        </div>

        <h2 class="text-xl font-bold text-slate-900">
          VIP Health Pass
        </h2>

        <p class="mt-2 text-2xl font-extrabold text-blue-700">
          ₹1,200 <span class="text-sm font-medium text-slate-500">/ saal</span>
        </p>

        <p class="mt-3 text-sm leading-6 text-slate-600">
          Saal bhar ki sehat ka pass. ₹1,200 ka NABL test karane par VIP Pass poore 1 saal ke liye active.
        </p>
      </div>

      <!-- NABL Lab Test -->
      <div class="rounded-2xl border border-green-100 bg-white p-6 shadow-sm transition hover:shadow-md">
        <div class="mb-4 flex h-12 w-12 items-center justify-center rounded-xl bg-green-100 text-2xl">
          🧪
        </div>

        <h2 class="text-xl font-bold text-slate-900">
          NABL Lab Test
        </h2>

        <p class="mt-2 text-lg font-bold text-green-700">
          Ghar se Sample
        </p>

        <p class="mt-3 text-sm leading-6 text-slate-600">
          Ghar se sample collection. Aapki report 100% Private Lock me rahegi.
        </p>
      </div>

      <!-- Health Vault -->
      <div class="rounded-2xl border border-indigo-100 bg-white p-6 shadow-sm transition hover:shadow-md">
        <div class="mb-4 flex h-12 w-12 items-center justify-center rounded-xl bg-indigo-100 text-2xl">
          🔐
        </div>

        <h2 class="text-xl font-bold text-slate-900">
          Health Vault
        </h2>

        <p class="mt-2 text-lg font-bold text-indigo-700">
          AES-256 Locked
        </p>

        <p class="mt-3 text-sm leading-6 text-slate-600">
          Saari health reports ek jagah. AES-256 lock me safe digital storage.
        </p>
      </div>

    </div>

    <!-- VIP Pass CTA -->
    <div class="mt-12 text-center">
      <a
        href="#"
        class="inline-flex w-full items-center justify-center rounded-xl bg-blue-700 px-8 py-4 text-lg font-bold text-white shadow-lg transition hover:bg-blue-800 sm:w-auto"
      >
        VIP Health Pass Lo - ₹1,200 / Saal
      </a>

      <p class="mt-4 text-sm text-slate-500">
        Aapki sehat, aapka parivaar, aapka trusted medical store.
      </p>
    </div>

    <!-- Trust Footer -->
    <div class="mt-12 rounded-2xl border border-slate-200 bg-white px-6 py-5 text-center">
      <p class="text-sm font-medium leading-6 text-slate-700">
        Chemist ko Cash nahi, SaaS Credit milta hai.
        Report pehle Lock hoti hai, phir save hoti hai.
      </p>
    </div>

  </div>
</section>

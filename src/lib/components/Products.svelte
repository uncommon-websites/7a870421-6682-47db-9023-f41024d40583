<script>
  import SectionLabel from './SectionLabel.svelte';
</script>

<section class="bg-black px-6 py-24 border-t border-gray-900">
  <div class="max-w-[1400px] mx-auto grid grid-cols-1 lg:grid-cols-12 gap-12">
    <div class="lg:col-span-3">
      <SectionLabel label="How It Works" />
    </div>
    
    <div class="lg:col-span-9">
      <div class="mb-16">
        <h2 class="text-4xl md:text-5xl text-white font-bold mb-2">
          Automated strategies
        </h2>
        <h2 class="text-4xl md:text-5xl text-gray-500">
          that maximize your yield
        </h2>
      </div>

    <div class="grid gap-6">
      <!-- Item 1 -->
      <a href="/" class="group relative bg-gradient-to-br from-primary-900/10 to-transparent border border-primary-700/20 rounded-2xl p-8 hover:border-primary-600/50 transition-all overflow-hidden">
        <div class="absolute inset-0 bg-gradient-to-r from-primary-600/0 via-primary-600/5 to-primary-600/0 translate-x-[-100%] group-hover:translate-x-[100%] transition-transform duration-1000"></div>
        <div class="relative grid grid-cols-1 md:grid-cols-12 gap-6">
          <div class="md:col-span-4">
            <div class="text-xs text-primary-400 mb-2 font-medium">Maximize returns</div>
            <h3 class="text-3xl font-bold text-white">Cross-Chain Rebalancing</h3>
          </div>
          <div class="md:col-span-7">
            <p class="text-gray-400 leading-relaxed text-lg">
              Blend automatically moves your assets to the highest-yielding opportunities across multiple blockchains, optimizing returns without manual intervention.
            </p>
          </div>
          <div class="md:col-span-1 flex justify-end items-start pt-2">
            <svg class="w-6 h-6 text-primary-400 group-hover:text-primary-300 transform group-hover:translate-x-1 transition-all" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"></path></svg>
          </div>
        </div>
      </a>

      <!-- Item 2 -->
      <a href="/" class="group relative bg-gradient-to-br from-primary-900/10 to-transparent border border-primary-700/20 rounded-2xl p-8 hover:border-primary-600/50 transition-all overflow-hidden">
        <div class="absolute inset-0 bg-gradient-to-r from-primary-600/0 via-primary-600/5 to-primary-600/0 translate-x-[-100%] group-hover:translate-x-[100%] transition-transform duration-1000"></div>
        <div class="relative grid grid-cols-1 md:grid-cols-12 gap-6">
          <div class="md:col-span-4">
            <div class="text-xs text-primary-400 mb-2 font-medium">Eliminate FX risk</div>
            <h3 class="text-3xl font-bold text-white">Delta-Neutral Hedging</h3>
          </div>
          <div class="md:col-span-7">
            <p class="text-gray-400 leading-relaxed text-lg">
              Protect your yields from currency volatility with automated hedging strategies that maintain stable value in your preferred local currency.
            </p>
          </div>
          <div class="md:col-span-1 flex justify-end items-start pt-2">
            <svg class="w-6 h-6 text-primary-400 group-hover:text-primary-300 transform group-hover:translate-x-1 transition-all" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"></path></svg>
          </div>
        </div>
      </a>

      <!-- Item 3 -->
      <a href="/" class="group relative bg-gradient-to-br from-primary-900/10 to-transparent border border-primary-700/20 rounded-2xl p-8 hover:border-primary-600/50 transition-all overflow-hidden">
        <div class="absolute inset-0 bg-gradient-to-r from-primary-600/0 via-primary-600/5 to-primary-600/0 translate-x-[-100%] group-hover:translate-x-[100%] transition-transform duration-1000"></div>
        <div class="relative grid grid-cols-1 md:grid-cols-12 gap-6">
          <div class="md:col-span-4">
            <div class="text-xs text-primary-400 mb-2 font-medium">Your keys, your crypto</div>
            <h3 class="text-3xl font-bold text-white">Non-Custodial Vaults</h3>
          </div>
          <div class="md:col-span-7">
            <p class="text-gray-400 leading-relaxed text-lg">
              Your assets remain in audited Safe accounts that you control. Blend never has custody of your funds—you maintain full ownership at all times.
            </p>
          </div>
          <div class="md:col-span-1 flex justify-end items-start pt-2">
            <svg class="w-6 h-6 text-primary-400 group-hover:text-primary-300 transform group-hover:translate-x-1 transition-all" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"></path></svg>
          </div>
        </div>
      </a>
    </div>
  </div>
</section>

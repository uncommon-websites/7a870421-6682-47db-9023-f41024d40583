<script>
  import SectionLabel from './SectionLabel.svelte';
</script>

<section class="bg-black px-6 py-32">
  <div class="max-w-[1400px] mx-auto">
    <div class="mb-16">
      <div class="text-sm text-primary-400 font-medium mb-4 tracking-wide">Why Blend</div>
      <h2 class="font-serif text-5xl md:text-6xl leading-tight text-white mb-8 max-w-4xl">
        Stable yields in your local currency without the FX volatility
      </h2>
      <p class="text-gray-400 text-xl leading-relaxed max-w-3xl">
        Blend automatically rebalances your assets across chains and hedges currency risk, so you can earn DeFi yields without worrying about exchange rate fluctuations.
      </p>
    </div>
    
    <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mt-20">
      <div class="bg-gradient-to-br from-primary-900/20 to-transparent border border-primary-700/20 rounded-2xl p-8 hover:border-primary-600/40 transition-all">
        <div class="text-5xl font-bold text-white mb-2">$4.86M</div>
        <div class="text-sm text-gray-400">Total deposits</div>
      </div>
      <div class="bg-gradient-to-br from-primary-900/20 to-transparent border border-primary-700/20 rounded-2xl p-8 hover:border-primary-600/40 transition-all">
        <div class="text-5xl font-bold text-white mb-2">8+</div>
        <div class="text-sm text-gray-400">Currencies supported</div>
      </div>
      <div class="bg-gradient-to-br from-primary-900/20 to-transparent border border-primary-700/20 rounded-2xl p-8 hover:border-primary-600/40 transition-all">
        <div class="text-5xl font-bold text-white mb-2">100%</div>
        <div class="text-sm text-gray-400">Non-custodial</div>
      </div>
    </div>
  </div>
</section>

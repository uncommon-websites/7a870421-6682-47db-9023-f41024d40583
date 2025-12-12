<script lang="ts">
  import { slide } from 'svelte/transition';
  
  interface FAQItem {
    question: string;
    answer: string;
  }

  const faqs: FAQItem[] = [
    { question: "Is Blend non-custodial?", answer: "Yes, Blend is completely non-custodial. Your assets remain in audited Safe accounts that you control at all times. We never have custody of your funds—you maintain full ownership and can withdraw whenever you want." },
    { question: "How does automated rebalancing work?", answer: "Blend continuously monitors yield opportunities across multiple blockchains and DeFi protocols. When a better opportunity is identified, the system automatically moves your assets to maximize returns while maintaining your preferred risk profile." },
    { question: "What currencies are supported?", answer: "Blend currently supports 8+ major currencies including USD, EUR, GBP, JPY, and various stablecoins. We're constantly adding support for more currencies based on user demand." },
    { question: "How does FX hedging protect my yields?", answer: "Our delta-neutral hedging strategies use derivatives to offset currency volatility. This means you can earn DeFi yields while maintaining stable value in your local currency, protecting you from exchange rate fluctuations." },
    { question: "Has Blend been audited?", answer: "Yes, Blend's smart contracts have been audited by leading security firms. We prioritize security and transparency, with all audit reports publicly available on our documentation site." },
    { question: "What are the fees?", answer: "Blend charges a small performance fee on profits generated. There are no deposit or withdrawal fees. Our fee structure is transparent and competitive with other yield optimization platforms." },
    { question: "Which chains does Blend support?", answer: "Blend operates across multiple chains including Ethereum, Polygon, Arbitrum, Optimism, and Base. Our cross-chain infrastructure allows seamless movement of assets to capture the best yields regardless of chain." }
  ];

  let openIndex: number | null = null;

  function toggle(index: number) {
    openIndex = openIndex === index ? null : index;
  }
</script>

<section class="bg-[#f5f5f5] px-6 py-24">
  <div class="max-w-[1400px] mx-auto grid grid-cols-1 lg:grid-cols-12 gap-12">
    <div class="lg:col-span-4">
      <h2 class="text-4xl text-white font-bold mb-6">
        Frequently asked questions
      </h2>
      <a href="/" class="text-sm text-gray-400 border-b border-gray-700 pb-0.5 hover:border-gray-400 transition-colors">See all support</a>
    </div>
    
    <div class="lg:col-span-8">
      <div class="border-t border-gray-200">
        {#each faqs as faq, i}
          <div class="border-b border-gray-900">
            <button 
              class="w-full py-8 flex justify-between items-center text-left hover:bg-gray-900/30 transition-colors px-4 -mx-4 rounded-lg"
              on:click={() => toggle(i)}
            >
              <span class="text-xl text-white font-medium">{faq.question}</span>
              <span class="text-3xl font-light text-primary-400 ml-4 transition-transform" style="transform: rotate({openIndex === i ? '45deg' : '0deg'})">
                +
              </span>
            </button>
            {#if openIndex === i}
              <div transition:slide class="pb-8 px-4 text-gray-400 leading-relaxed text-lg">
                {faq.answer}
              </div>
            {/if}
          </div>
        {/each}
      </div>
    </div>
  </div>
</section>

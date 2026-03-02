<template>
  <section class="bg-gray-50 py-8 md:py-[60px]">
    <div class="container max-w-7xl mx-auto">
      <div class="flex flex-col md:flex-row md:items-start md:justify-between flex-wrap">
        <!-- Left Column: Text Content -->
        <div class="basis-full md:basis-[50%] p-[10px] flex flex-col gap-5 order-2 md:order-1">
          <h2 class="text-2xl md:text-4xl font-bold uppercase leading-snug" style="color: #00274D;">
            START YOUR CLAIM – QUICK, SECURE, AND FREE
          </h2>
          <p class="text-[16px] mb-[18px] text-gray-700 leading-relaxed">
            Whether your funds are connected to Louisiana or another state, Legacy Solutions LLC makes it easy to recover what’s rightfully yours. There are no upfront costs, and your information remains private. Complete the brief form below to verify eligibility and start your recovery process.
          </p>
          <p class="text-[16px] mb-[18px] text-gray-700 leading-relaxed">
            Serving all 64 Louisiana parishes and clients nationwide. Even if you’re unsure where your funds are located, our team can assist you from start to finish.
          </p>
          <img 
            src="/images/contact-section/CONTACT-FORM-SECTION-2.png" 
            alt="Contact form illustration"
            class="max-w-[85%]"
          />
        </div>

        <!-- Right Column: Form Card -->
        <div class="bg-white rounded-2xl shadow-sm basis-full md:basis-[50%] p-[25px] order-1 md:order-2">
          <form class="space-y-6">
            <!-- First / Last Name -->
            <div class="grid md:grid-cols-2 gap-4">
              <div class="space-y-2">
                <label class="block text-sm font-semibold text-gray-800">
                  First Name <span class="text-red-500 text-xs">(Required)</span>
                </label>
                <input
                  type="text"
                  class="w-full rounded-lg border border-gray-300 px-3 py-2 text-sm focus:outline-none focus:ring-2 focus:ring-[#FF9900] focus:border-transparent"
                  placeholder="Enter your full legal name."
                />
              </div>
              <div class="space-y-2">
                <label class="block text-sm font-semibold text-gray-800">
                  Last Name <span class="text-red-500 text-xs">(Required)</span>
                </label>
                <input
                  type="text"
                  class="w-full rounded-lg border border-gray-300 px-3 py-2 text-sm focus:outline-none focus:ring-2 focus:ring-[#FF9900] focus:border-transparent"
                  placeholder="Enter your full legal name."
                />
              </div>
            </div>

            <!-- Email / Confirm Email -->
            <div class="grid md:grid-cols-2 gap-4">
              <div class="space-y-2">
                <label class="block text-sm font-semibold text-gray-800">
                  Email Address <span class="text-red-500 text-xs">(Required)</span>
                </label>
                <input
                  type="email"
                  class="w-full rounded-lg border border-gray-300 px-3 py-2 text-sm focus:outline-none focus:ring-2 focus:ring-[#FF9900] focus:border-transparent"
                  placeholder="Enter Email"
                />
              </div>
              <div class="space-y-2">
                <label class="block text-sm font-semibold text-gray-800">
                  Confirm Email
                </label>
                <input
                  type="email"
                  class="w-full rounded-lg border border-gray-300 px-3 py-2 text-sm focus:outline-none focus:ring-2 focus:ring-[#FF9900] focus:border-transparent"
                  placeholder="Confirm Email"
                />
              </div>
            </div>

            <!-- Phone / Other Claimants -->
            <div class="grid md:grid-cols-2 gap-4">
              <div class="space-y-2">
                <label class="block text-sm font-semibold text-gray-800">
                  Phone Number <span class="text-red-500 text-xs">(Required)</span>
                </label>
                <input
                  type="tel"
                  class="w-full rounded-lg border border-gray-300 px-3 py-2 text-sm focus:outline-none focus:ring-2 focus:ring-[#FF9900] focus:border-transparent"
                  placeholder="Write Phone Number without +1"
                />
                <p class="text-[11px] text-gray-500">
                  Please enter your phone number without +1.
                </p>
              </div>
              <div class="space-y-2">
                <label class="block text-sm font-semibold text-gray-800">
                  Other Potential Claimants
                </label>
                <input
                  type="text"
                  class="w-full rounded-lg border border-gray-300 px-3 py-2 text-sm focus:outline-none focus:ring-2 focus:ring-[#FF9900] focus:border-transparent"
                  placeholder="List any family members"
                />
              </div>
            </div>

            <!-- Parish / Preferred Contact -->
            <div class="grid md:grid-cols-2 gap-4">
              <div class="space-y-2">
                <label class="block text-sm font-semibold text-gray-800">
                  Parish or County (if known)
                </label>
                <input
                  type="text"
                  class="w-full rounded-lg border border-gray-300 px-3 py-2 text-sm focus:outline-none focus:ring-2 focus:ring-[#FF9900] focus:border-transparent"
                  placeholder="Parish or County (if known)"
                />
              </div>
              <div class="space-y-2">
                <label class="block text-sm font-semibold text-gray-800">
                  Preferred Contact Method
                </label>
                <input
                  type="text"
                  class="w-full rounded-lg border border-gray-300 px-3 py-2 text-sm focus:outline-none focus:ring-2 focus:ring-[#FF9900] focus:border-transparent"
                  placeholder="Write Phone Number"
                />
              </div>
            </div>

            <!-- State / Approximate Amount -->
            <div class="grid md:grid-cols-2 gap-4">
              <div class="space-y-2">
                <label class="block text-sm font-semibold text-gray-800">
                  State Where Funds Are Located <span class="text-red-500 text-xs">(Required)</span>
                </label>
                <select
                  class="w-full rounded-lg border border-gray-300 px-3 py-2 text-sm bg-white focus:outline-none focus:ring-2 focus:ring-[#FF9900] focus:border-transparent"
                >
                  <option>Louisiana</option>
                  <option>Other / Not Sure</option>
                </select>
              </div>
              <div class="space-y-2">
                <label class="block text-sm font-semibold text-gray-800">
                  Approximate Claim Amount
                </label>
                <select
                  class="w-full rounded-lg border border-gray-300 px-3 py-2 text-sm bg-white focus:outline-none focus:ring-2 focus:ring-[#FF9900] focus:border-transparent"
                >
                  <option>Approximate Claim Amount</option>
                  <option>$5,000 - $15,000</option>
                  <option>$16,000 - $32,000</option>
                  <option>$33,000 - $58,000</option>
                  <option>$58,000+</option>
                  <option>Not Sure</option>
                </select>
              </div>
            </div>

            <!-- Type of Funds -->
            <div class="space-y-2">
              <label class="block text-sm font-semibold text-gray-800">
                Type of Funds <span class="text-red-500 text-xs">(Required)</span>
              </label>
              <div class="grid grid-cols-1 gap-2 text-sm text-gray-700">
                <label class="flex items-center space-x-2">
                  <input type="radio" name="fundType" class="text-[#FF9900] border-gray-300" />
                  <span>Property Settlement</span>
                </label>
                <label class="flex items-center space-x-2">
                  <input type="radio" name="fundType" class="text-[#FF9900] border-gray-300" />
                  <span>Inheritance</span>
                </label>
                <label class="flex items-center space-x-2">
                  <input type="radio" name="fundType" class="text-[#FF9900] border-gray-300" />
                  <span>Tax Sale Surplus</span>
                </label>
                <label class="flex items-center space-x-2">
                  <input type="radio" name="fundType" class="text-[#FF9900] border-gray-300" />
                  <span>401(k) or Retirement Account</span>
                </label>
                <label class="flex items-center space-x-2">
                  <input type="radio" name="fundType" class="text-[#FF9900] border-gray-300" />
                  <span>Insurance Payout</span>
                </label>
                <label class="flex items-center space-x-2">
                  <input type="radio" name="fundType" class="text-[#FF9900] border-gray-300" />
                  <span>Expropriation or Taking</span>
                </label>
                <label class="flex items-center space-x-2">
                  <input type="radio" name="fundType" class="text-[#FF9900] border-gray-300" />
                  <span>Other</span>
                </label>
              </div>
            </div>

            <!-- Brief Description -->
            <div class="space-y-2">
              <label class="block text-sm font-semibold text-gray-800">
                Brief Description of Funds (if known)
              </label>
              <textarea
                rows="3"
                class="w-full rounded-lg border border-gray-300 px-3 py-2 text-sm resize-y focus:outline-none focus:ring-2 focus:ring-[#FF9900] focus:border-transparent"
                placeholder="Enter a brief description of the funds"
              ></textarea>
            </div>

            <!-- How Did You Hear / Who Are You Contacting As -->
            <div class="grid md:grid-cols-2 gap-4">
              <div class="space-y-2">
                <label class="block text-sm font-semibold text-gray-800">
                  How Did You Hear About Us?
                </label>
                <select
                  class="w-full rounded-lg border border-gray-300 px-3 py-2 text-sm bg-white focus:outline-none focus:ring-2 focus:ring-[#FF9900] focus:border-transparent"
                >
                  <option>Friend or Family</option>
                  <option>Online Search</option>
                  <option>Social Media</option>
                  <option>Attorney / Professional</option>
                  <option>Other</option>
                </select>
              </div>
              <div class="space-y-2">
                <label class="block text-sm font-semibold text-gray-800">
                  Who Are You Contacting Us As? <span class="text-red-500 text-xs">(Required)</span>
                </label>
                <div class="space-y-2 text-sm text-gray-700">
                  <label class="flex items-center space-x-2">
                    <input type="radio" name="contactAs" class="text-[#FF9900] border-gray-300" />
                    <span>Individual or Family</span>
                  </label>
                  <label class="flex items-center space-x-2">
                    <input type="radio" name="contactAs" class="text-[#FF9900] border-gray-300" />
                    <span>Business or Recovery Specialist</span>
                  </label>
                </div>
              </div>
            </div>

            <!-- Company / Website -->
            <div class="grid md:grid-cols-2 gap-4">
              <div class="space-y-2">
                <label class="block text-sm font-semibold text-gray-800">
                  Company Name
                </label>
                <input
                  type="text"
                  class="w-full rounded-lg border border-gray-300 px-3 py-2 text-sm focus:outline-none focus:ring-2 focus:ring-[#FF9900] focus:border-transparent"
                  placeholder="Company Name"
                />
              </div>
              <div class="space-y-2">
                <label class="block text-sm font-semibold text-gray-800">
                  Website (optional)
                </label>
                <input
                  type="url"
                  class="w-full rounded-lg border border-gray-300 px-3 py-2 text-sm focus:outline-none focus:ring-2 focus:ring-[#FF9900] focus:border-transparent"
                  placeholder="Website (optional)"
                />
              </div>
            </div>

            <!-- How can we work together? -->
            <div class="space-y-2">
              <label class="block text-sm font-semibold text-gray-800">
                How can we work together? <span class="text-red-500 text-xs">(Required)</span>
              </label>
              <textarea
                rows="3"
                class="w-full rounded-lg border border-gray-300 px-3 py-2 text-sm resize-y focus:outline-none focus:ring-2 focus:ring-[#FF9900] focus:border-transparent"
                placeholder="Briefly explain how ?"
              ></textarea>
            </div>

            <!-- Authorization Checkbox -->
            <div class="flex items-start space-x-3">
              <input
                type="checkbox"
                class="mt-1 h-4 w-4 rounded border-gray-300 text-[#FF9900] focus:ring-[#FF9900]"
              />
              <p class="text-xs md:text-sm text-gray-700">
                I authorize Legacy Solutions LLC to review my eligibility for available funds and contact me regarding my claim.
              </p>
            </div>

            <!-- Next Step Notice -->
            <div class="border-l-4 border-[#FF9900] bg-[#FFF5E6] px-3 py-3 text-xs md:text-sm text-gray-800 rounded-md">
              <span class="font-semibold text-[#FF9900]">Next step:</span>
              <span class="ml-1">
                You will be prompted to review and sign a secure authorization.
              </span>
            </div>

            <!-- Submit Button -->
            <div class="pt-2">
              <button
                type="button"
                class="w-full bg-[#FF9900] hover:bg-[#e58600] text-white font-bold uppercase rounded-xl py-3 md:py-4 text-sm md:text-base tracking-wide shadow-md transition-colors"
              >
                CONTINUE TO AUTHORIZATION
              </button>
            </div>
          </form>
        </div>
      </div>
    </div>
  </section>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'CTASection',
});
</script>

<style scoped>
</style>

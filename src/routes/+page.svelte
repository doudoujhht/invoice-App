<svelte:body class="flex"/>


<nav class="w-[10vw]">
	s
</nav>

<main class="w-[90vw] px-[20vw]">
	<div>
		<div>
			<h1>Invoices</h1>
			<p>There are 7 total invoices</p>
		</div>
		<div>
			<div>
				<span>Filter by status</span>
				<svg width="11" height="7" xmlns="http://www.w3.org/2000/svg"><path d="M1 1l4.228 4.228L9.456 1" stroke="#7C5DFA" stroke-width="2" fill="none" fill-rule="evenodd"/></svg>
			</div>
			<button>
				<div><svg width="11" height="11" xmlns="http://www.w3.org/2000/svg"><path d="M6.313 10.023v-3.71h3.71v-2.58h-3.71V.023h-2.58v3.71H.023v2.58h3.71v3.71z" fill="#7C5DFA" fill-rule="nonzero"/></svg></div>
				<span>New Invoice</span>
			</button>
		</div>
	</div>
	<div class="flex items-center w-full justify-around py-4 rounded-xl invoice">
		<div class="headingM"><span class="text-[#7E88C3]">#</span><span class="">RT3080</span></div>
		<span class="body text-coolGray">Due  19 Aug 2021</span>
		<span class="body text-coolGray">Jensen Huang</span>
		<span class="headingM">£ 1,800.90</span>
		<div class="text-green flex items-center gap-3 bg-green bg-opacity-[10%] px-5 py-2 rounded-md"><div class="w-[8px] h-[8px] bg-[currentColor] rounded"></div> <span class="text-[currentColor] headingS">Paid</span></div>
		<svg width="7" height="10" xmlns="http://www.w3.org/2000/svg"><path d="M1 1l4 4-4 4" stroke="#7C5DFA" stroke-width="2" fill="none" fill-rule="evenodd"/></svg>
	</div>
</main>

<style>
	.invoice{
		background: #FFFFFF;
		box-shadow: 0px 10px 10px -10px rgba(72, 84, 159, 0.100397);
	}
</style>

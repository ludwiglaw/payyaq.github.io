		
	<link rel="stylesheet" href="https://api.epay.com/paymentApi/css/exchange.css?v=20170807" />
	<script src="https://api.epay.com/paymentApi/js/jquery-1.9.1.js"></script>
	<script src="https://api.epay.com/paymentApi/js/exchange3.js?v=20170807"></script>

<input type="hidden" id="merchant_epay_account" value="ella@epay.com">
<div id="formDiv"></div>
<div class="width-w">
	<div class="width-mg">
		<div class="bj-color"><span>E-currency  exchange</span></div>

		<div class="width-fl">
			<ul>
				<li>
					<p class="li-p">Send: </p>
					<select id="depositType" class="li-select">
						<option>Select</option>
						<option value="01_1">Perfect Money USD</option>
						<option value="01_2">Perfect Money EUR</option>
						<option value="05_1">OKPAY USD</option>
						<option value="05_2">OKPAY EUR</option>
						<option value="06_1">Payeer USD</option>
						<option value="06_2">Payeer EUR</option>
						<option value="02_1">AdvCash USD</option>
						<option value="02_2">AdvCash EUR</option>
						<option value="08_1">Fasapay USD</option>
					</select>
				</li>
				<li><img src="https://api.epay.com/paymentApi/images/next-icon_03.png" class="li-img"/></li>
				<li>
					<p class="li-p">Receive: </p>
					<select id="withdrawType" class="li-select">
						<option>Select</option>
					</select>
				</li>
				<li>
					<div class="li-left">
						<p class="li-p">You send amount:</p>
						<input id="AMOUNT" onkeyup="clearNum(this);" onblur="loadTureAmount();" type="text" class="li-input" />
					</div>
				</li>
				<li>
					<div class="li-left">
						<p class="li-p">You receive amount:</p>
						<b id="trueAmount" class="green-text">0.00</b>
					</div>
				</li>
				<li>
					<div class="li-left">
						<p class="li-p">Account:</p>
						<input id="WITHDRAW_ACCOUNT" type="text" class="li-input" />
					</div>
				</li>
				<li>
					<div class="li-left">
						<p class="li-p">Contact Email:</p>
						<input id="EMAIL" type="text" class="li-input" />
					</div>
				</li>
				<li>
					<p class="li-bluebtn"><span class="pointer" onclick="confirm();">Exchange</span></p>
				</li>
			</ul>
		</div>
		<p class="bottom-with">Powered by  <a href="https://www.epay.com">Epay.com</a></p>
	</div>
	</div>
		
	<input type="hidden" id="merchant_epay_account" value="ludwig.luo@gmail.com"><input type="hidden" id="merchant_epay_account" value="ludwig.luo@gmail.com">

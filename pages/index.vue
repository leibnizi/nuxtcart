<template>
	<section class="container">
		<div class="page-group">
			<div class="page page-current">
                <!--结算底部-->
				<div class="footer_cart">
					<div class="row no-gutter">
						<span class="col-75 action">
							<span class="pull-right" style="float:left;color: black;">合计：<em class="price"><small>￥</small><i id="all-price">0</i></em></span>
						</span>
						<span style="float: right;" class="col-25">
							<button type="button" data-action="main.generate" class="button button-big button-block button_order">下订单</button>
							<button style="border:none;display:none;width:100%;height: 46px;" class="cart_del">删除</button>
						</span>
					</div>
				</div>
                <main class="content">
                    <!-- 顶部 -->
						<div style="height: 30px;border-bottom: 1px solid #ddd;" class="">
							<span class="action">
								<label style="padding-top: 4px;" class="label-checkbox pull-left" id="check-all">
									<input type="checkbox" name="check-all">
									<div class="cart_sellect_all">全选</div>
								</label>
							</span>
							<p class="cart_finish" style="float: right;font-size: 14px;">
								<a class="pull-left content-fluid">
									编辑
								</a>
							</p>
						</div>
					<div class="order_list">
                        <article class="order_content">
							<div class="order-body">
								<div class="list-block media-list">
									<ul>
                                        <li>
											<div class="item_content">
												<label class="label-checkbox check-list item-media" >
													<input type="checkbox" name="check-list" data-id="15816">
													<div class="item-media"><i class="icon icon-form-checkbox"></i></div>
												</label>
												<a class="item_img" href="#"><img src="product1.png" external></a>
												<a class="item-inner item-info1" external>
													<div class="item-title">正品和田白玉生肖羊吊坠</div>
													<span class="font_ccc col-70 orderfont2">规格：暂无规格</span>                                                                                         												<div class="row no-gutter">
													<span class="font_red col-40">
														<em class="price">
															<i class="unitprice">2570.00</i>
														</em>
														宝额
													</span>
														<div style="margin-left:43%;" class="item-edit col-60">
															<div class="product_num">
																<span style="border-right:none;" class="product_minus">
																	-
																</span>
																<span class="num_input">
																																															<input type="number" class="evenum" autocomplete="off" name="quantity" max="1" min="1" value="1">
																</span>
																<span style="border-left:none;" class="product_plus">
																	+
																</span>
															</div>
														</div>
													</div>
												</a>
											</div>
										</li>
                                    </ul>
								</div>
							</div>
						</article>
                    </div>
				</main>
			</div>
		</div>
	</section>
</template>

<script>
	export default {

	}
</script>

<style>
ul, ol, li {
	list-style: none;
}
.footer_cart {
	position: absolute;
	bottom: 0;
	width: 100%;
}
.cart_sellect_all {
	display: inline-block;
}
.item_content {
	padding-left: .75rem;
	display: -webkit-box;
	display: -webkit-flex;
	display: flex;
	-webkit-box-pack: justify;
	-webkit-justify-content: space-between;
	justify-content: space-between;
	-webkit-box-align: center;
	-webkit-align-items: center;
	align-items: center;
}
.product_num {
	height: 100%;
	width: 100%;
}
.product_minus {
	border: 1px solid #ddd;
	border-radius: 0;
	display: inline-block;
	width: 20px;
	height: 20px;
	text-align: center;
	background-size: 20px auto;
	vertical-align: middle;
}
.num_input {
	height: 100%;
    width: 25px;
	color: #000000;
    font-size: 12px;
    border: 1px solid rgba(0, 0, 0, 0.15);
	background: none;
	line-height: inherit;
	border-radius: 0;
	display: inline-block;
	text-align: center;
}
.num_input input {
	height: 18px;
	text-align: center;
}
.num_input2 {
	height: 18px;
	width: 100%;
	line-height: 1rem;
    border-radius: 3px;
    padding-left: 0;
    font-size: 10px;
	text-align: center;
	border: 0;
}
.product_plus {
	border: 1px solid #ddd;
    border-radius: 0;
	display: inline-block;
	width: 20px;
	height: 20px;

	background-size: 20px auto;
	vertical-align: middle;
	text-align: center;
}
.item_img img {
	width: 70px;
}

</style>

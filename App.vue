<script>
	export default {
		onLaunch: function() {
			this.$store.state.userInfo = uni.getStorageSync('userInfo')
			console.log(this.$store.state.userInfo)
		},
		onShow: function() {
			
		},
		onHide: function() {
			
		}
	}
</script>

<style>
	/*每个页面公共css */
	.flex {
	    display: flex
	}
	
	.j-star {
	    justify-content: flex-start;
	}
	
	.j-end {
	    justify-content: flex-end;
	}
	
	.j-center {
	    justify-content: center;
	}
	
	.f-column {
	    flex-direction: column;
	}
	
	.a-center {
	    align-items: center;
	}
	
	.f-wrap {
	    flex-wrap: wrap;
	}
	
	.j-between {
	    justify-content: space-between;
	}
	
	.j-around {
	    justify-content: space-around;
	}
	
	.ellipsis {
	    overflow: hidden;
	    text-overflow: ellipsis;
	    white-space: nowrap;
	}
	
	.ellipsiss {
	    overflow: hidden;
	    text-overflow: ellipsis;
	    display: -webkit-box;
	    -webkit-line-clamp: 3;
	    -webkit-box-orient: vertical;
	}
	
	.border {
	    border: 1rpx rgb(226, 223, 223) solid;
	}
	
	.border-bottom {
	    border-bottom: 1rpx rgb(226, 223, 223) solid;
	}
</style>

<template>
  <DropZone ncBgType="bgColor" backgroundImage="" id="7076658f-17b6-4562-bbc2-93a4bd571f60"
    v-bind:style="{'width':'100%','height':'auto'}">
    <WDefaultCheckbox size="md" label="I accept the terms and use" v-bind:plain="false" theme="theme--light01"
      v-bind:value="true" v-bind:inline="false" fontSize="14px" v-bind:autofocus="false" v-bind:isEnabled="true"
      textAlign="left" fontFamily="Roboto-Regular,Roboto" fontWeight="normal" ncTypography="custom"
      v-bind:indeterminate="false" labelPosition="right" ncTooltipText="" v-bind:checkboxSwitch="true"
      v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'boolean','propName':'value','displayName':'Value'},{'type':'string','propName':'label','displayName':'Display'}]}"
      ncFocusFontColor="black" ncHoverFontColor="black" ncDisableFontColor="black" ncFocusBorderColor="black"
      ncHoverBorderColor="black" ncDisableBorderColor="black" ncFocusBackgroundColor="transparent"
      ncHoverBackgroundColor="transparent" ncDisableBackgroundColor="transparent" position="relative"
      id="dde43382-832e-4081-b7f5-b08c59f3c433"
      v-bind:style="{'color':'','width':'100%','height':'100%','tabIndex':'0px','boxShadow':'','fontStyle':'none','marginTop':'0px','lineHeight':'','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'none','zIndex':2}"/>
    <WCalendar v-bind:fade="false" text="Text Content 1" theme="theme--light01" ImgAlt="Blank Image 1"
      v-bind:noWrap="false" caption="Carousel 1" v-bind:noTouch="false"
      imageUrl="https://picsum.photos/500/250/?image=1082" v-bind:interval="5000" v-bind:isEnabled="true" background=""
      blankColor="#ababab" v-bind:indicators="false" secondText="Text Content 2" v-bind:noAnimation="false"
      ncTypography="body2" v-bind:noHoverPause="false" secondImgAlt="Blank Image 2" secondCaption="Carousel 2"
      v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'imageUrl','displayName':'ImageUrl'},{'type':'string','propName':'secondImageUrl','displayName':'SecondImageUrl'}]}"
      secondImageUrl="https://picsum.photos/500/250/?image=1002" ncClickBorderColor="black" ncHoverBorderColor="black"
      dataModelForDynamicType="string" position="relative" id="10bda2b5-97de-42d1-a1d4-36a89fd26894"
      v-bind:style="{'width':'100%','height':'100%','boxShadow':'','fontStyle':'normal','marginTop':'0px','fontFamily':'OpenSans-Bold,Open Sans','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'0px','borderTopRightRadius':'0px','borderBottomLeftRadius':'0px','borderBottomRightRadius':'0px','zIndex':3}"/>
    <WTimeInput id="7267b7ca-46b4-47cc-a716-15c800f0b697" v-bind:lazy="false" size="md" text="" v-bind:trim="false"
      v-bind:noWheel="false" v-bind:disabled="false" v-bind:readonly="false" v-bind:required="false" wordList=""
      v-bind:autofocus="false" v-bind:plaintext="false" background="" ariaInvalid="false" v-bind:debounceVal="0"
      ncInputType="time" placeholder="" v-bind:previewMode="true" autocomplete="" ncTypography="body1"
      v-bind:lazyFormatter="false" ncTooltipText="" v-bind:isWordListOpen="false"
      v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':true,'structure':[{'type':'string','ncKey':'type','ncType':{'ncInputType':'number'},'ncValue':'number','propName':'text','displayName':'Value','nsDefaultValue':'string'}]}"
      v-bind:isNumberConvert="false" ncClickFontColor="#434855" ncFocusFontColor="#434855" ncHoverFontColor="#434855"
      ncMaxNumberValue="100" ncMinNumberValue="0" ncClickBorderColor="#000000" ncDisableFontColor="#434855"
      ncFocusBorderColor="#000000" ncHoverBorderColor="#000000" ncDisableBorderColor="#000000" formatterFunctionName=""
      ncClickBackgroundColor="#ffffff" ncFocusBackgroundColor="#ffffff" ncHoverBackgroundColor="#ffffff"
      ncDisableBackgroundColor="#ffffff" position="relative" v-bind:snapX="false" v-bind:snapY="false"
      v-bind:style="{'color':'','width':'100%','height':'100%','boxShadow':'','fontStyle':'normal','marginTop':'0px','textAlign':'left','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','lineHeight':'1','marginLeft':'0px','paddingTop':'0px','visibility':'visible','borderColor':'#D1D1D6','borderStyle':'solid','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'none','zIndex':4}"/>
    <WFile id="be14c9cd-76bc-49b3-9bf3-094f9820b85e" form="" name="" size="md" plain="false" accept=""
      v-bind:noDrop="false" v-bind:capture="false" v-bind:disabled="false" v-bind:multiple="false"
      v-bind:required="false" v-bind:autoFocus="false" dataModel="file-binary" v-bind:directory="false"
      browseText="Browse" v-bind:noTraverse="false" placeholder="No file chosen"
      v-bind:nucalDataModel="{'type':'NSW','isList':true,'update':{'dataModel':'dataModel'},'dynamic':true,'structure':[{'type':'file-binary','update':{'dataModel':'dataModel'},'propName':'value','displayName':'Value'}]}"
      dropPlaceholder="Drop files here" noDropPlaceholder="Not allowed" position="relative"
      v-bind:style="{'width':'100%','height':'100%','marginTop':'0px','marginLeft':'0px','paddingTop':'0px','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','zIndex':5}"/>
  </DropZone>
</template>
<script>
export default {
  name: 'Screen1',
  data() {
    return {};
  },
  props: {},
  created() {},
  mounted() {},
  computed: {},
  methods: {},
  watch: {},
};
</script>

<style lang="scss" scoped>
@media (min-width: 1024.05px){[id='7076658f-17b6-4562-bbc2-93a4bd571f60'] {
             display: grid; 
             grid-template-columns: 12.96844482421875rem 6.796875rem 2.76397705078125rem 19.53125rem 6.40625rem 9.375rem 0.46875rem 17.96875rem 23.720703125rem;
             grid-template-rows: minmax(16.40625rem, max-content) minmax(2.5rem, max-content) minmax(5.13671875rem, max-content) minmax(5.46875rem, max-content) minmax(8.359375rem, max-content) minmax(13.046875rem, max-content) minmax(2.1875rem, max-content) minmax(19.140625rem, max-content) minmax(10.56640625rem, max-content);
          }
[id='dde43382-832e-4081-b7f5-b08c59f3c433']{
          grid-area: 4/6/5/7;
          
          
          }
[id='10bda2b5-97de-42d1-a1d4-36a89fd26894']{
          grid-area: 6/4/9/5;
          font-size: Max(Min(12rem, 12px),0.9375rem);
          
          }
[id='7267b7ca-46b4-47cc-a716-15c800f0b697']{
          grid-area: 2/2/3/3;
          font-size: Max(Min(12rem, 12px),0.9375rem);
          
          }
[id='be14c9cd-76bc-49b3-9bf3-094f9820b85e']{
          grid-area: 7/8/8/9;
          font-size: Max(Min(16rem, 12px),1.25rem);
          
          }}

@media (min-width: 768.05px) and (max-width: 1024px){[id='7076658f-17b6-4562-bbc2-93a4bd571f60'] {
             display: grid; 
             grid-template-columns: 16.40625rem 24.4140625rem 3.3203125rem 1.611328125rem 8.49609375rem 1.611328125rem 5.2734375rem 22.4609375rem 16.40625rem;
             grid-template-rows: minmax(20.5078125rem, max-content) minmax(3.125rem, max-content) minmax(6.4208984375rem, max-content) minmax(6.8359375rem, max-content) minmax(10.44921875rem, max-content) minmax(16.30859375rem, max-content) minmax(2.734375rem, max-content) minmax(23.92578125rem, max-content) minmax(3.125rem, max-content);
          }
[id='dde43382-832e-4081-b7f5-b08c59f3c433']{
          grid-area: 4/4/5/7;
          
          
          }
[id='10bda2b5-97de-42d1-a1d4-36a89fd26894']{
          grid-area: 6/2/9/3;
          font-size: Max(Min(12rem, 12px),1.171875rem);
          
          }
[id='7267b7ca-46b4-47cc-a716-15c800f0b697']{
          grid-area: 2/5/3/6;
          font-size: Max(Min(12rem, 12px),1.171875rem);
          
          }
[id='be14c9cd-76bc-49b3-9bf3-094f9820b85e']{
          grid-area: 7/8/8/9;
          font-size: Max(Min(16rem, 12px),1.5625rem);
          
          }}

@media (min-width: 480.05px) and (max-width: 768px){[id='7076658f-17b6-4562-bbc2-93a4bd571f60'] {
             display: grid; 
             grid-template-columns: 33.723958333333336rem 1.302083333333334rem 7.16145833333333rem 2.1484375rem 11.328125rem 2.1484375rem 7.161458333333336rem 1.3020833333333321rem 33.723958333333336rem;
             grid-template-rows: minmax(27.34375rem, max-content) minmax(4.166666666666667rem, max-content) minmax(8.561197916666666rem, max-content) minmax(9.114583333333334rem, max-content) minmax(13.932291666666666rem, max-content) minmax(57.29166666666667rem, max-content) minmax(4.166666667rem, max-content) minmax(3.6458333333333335rem, max-content) minmax(4.166666667rem, max-content);
          }
[id='dde43382-832e-4081-b7f5-b08c59f3c433']{
          grid-area: 4/4/5/7;
          
          
          }
[id='10bda2b5-97de-42d1-a1d4-36a89fd26894']{
          grid-area: 6/2/7/9;
          font-size: Max(Min(12rem, 12px),1.5625rem);
          
          }
[id='7267b7ca-46b4-47cc-a716-15c800f0b697']{
          grid-area: 2/5/3/6;
          font-size: Max(Min(12rem, 12px),1.5625rem);
          
          }
[id='be14c9cd-76bc-49b3-9bf3-094f9820b85e']{
          grid-area: 8/3/9/8;
          font-size: Max(Min(16rem, 12px),2.0833333333333335rem);
          
          }}

@media (min-width: 375.05px) and (max-width: 480px){[id='7076658f-17b6-4562-bbc2-93a4bd571f60'] {
             display: grid; 
             grid-template-columns: 23.958333333333332rem 2.0833333333333357rem 11.458333333333332rem 3.4375rem 18.125rem 3.4375rem 11.458333333333329rem 2.0833333333333357rem 23.958333333333332rem;
             grid-template-rows: minmax(43.75rem, max-content) minmax(6.666666666666667rem, max-content) minmax(13.697916666666666rem, max-content) minmax(14.583333333333334rem, max-content) minmax(22.291666666666668rem, max-content) minmax(91.66666666666666rem, max-content) minmax(5rem, max-content) minmax(5.833333333333333rem, max-content) minmax(5rem, max-content);
          }
[id='dde43382-832e-4081-b7f5-b08c59f3c433']{
          grid-area: 4/4/5/7;
          
          
          }
[id='10bda2b5-97de-42d1-a1d4-36a89fd26894']{
          grid-area: 6/2/7/9;
          font-size: Max(Min(12rem, 12px),2.5rem);
          
          }
[id='7267b7ca-46b4-47cc-a716-15c800f0b697']{
          grid-area: 2/5/3/6;
          font-size: Max(Min(12rem, 12px),2.5rem);
          
          }
[id='be14c9cd-76bc-49b3-9bf3-094f9820b85e']{
          grid-area: 8/3/9/8;
          font-size: Max(Min(16rem, 12px),3.3333333333333335rem);
          
          }}

@media (min-width: 0px) and (max-width: 375px){[id='7076658f-17b6-4562-bbc2-93a4bd571f60'] {
             display: grid; 
             grid-template-columns: 6.4rem 0 10.266666666666673rem 2.666666666666668rem 61.333333333333336rem 2.6666666666666643rem 10.266666666666666rem 0 6.4rem;
             grid-template-rows: minmax(56rem, max-content) minmax(32.0735632183908rem, max-content) minmax(17.533333333333335rem, max-content) minmax(50.866666666666674rem, max-content) minmax(28.533333333333335rem, max-content) minmax(117.33333333333333rem, max-content) minmax(6.4rem, max-content) minmax(7.466666666666667rem, max-content) minmax(6.4rem, max-content);
          }
[id='dde43382-832e-4081-b7f5-b08c59f3c433']{
          grid-area: 4/3/5/8;
          
          
          }
[id='10bda2b5-97de-42d1-a1d4-36a89fd26894']{
          grid-area: 6/4/7/7;
          font-size: Max(Min(12rem, 12px),3.2rem);
          
          }
[id='7267b7ca-46b4-47cc-a716-15c800f0b697']{
          grid-area: 2/2/3/9;
          font-size: Max(Min(12rem, 12px),12.027586206896553rem);
          
          }
[id='be14c9cd-76bc-49b3-9bf3-094f9820b85e']{
          grid-area: 8/5/9/6;
          font-size: Max(Min(16rem, 12px),4.266666666666667rem);
          
          }}
</style>
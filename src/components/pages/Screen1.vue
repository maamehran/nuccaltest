<template>
  <NucGridPage v-bind:gap="{'row':0,'col':0}" v-bind:designMode="false" overflow="auto" v-bind:rows="[1]"
    v-bind:columns="[1]"
    v-bind:schema="{'r0-c0':{'row':0,'col':0,'rowSpan':1,'colSpan':1,'showIn':['xs','sm','md','lg']}}"
    v-bind:minNsLimit="158"
    v-bind:style="{'background':'#FFFFFF','paddingTop':'0px','paddingBottom':'0px','paddingLeft':'0px','paddingRight':'0px'}">
    <NucGridCell v-bind:wrap="true" v-bind:reverse="false" overflow="hidden" direction="column"
      v-bind:showInDevice="['xs','sm','md','lg']" verticalAlignment="top" horizontalAlignment="left" v-bind:row="0"
      v-bind:col="0" v-bind:rowSpan="1" v-bind:colSpan="1" v-bind:marginLeft="0" v-bind:marginRight="0"
      v-bind:marginTop="0" v-bind:marginBottom="0" id="03cab6af-398f-496e-b637-02e19899ef45"
      v-bind:style="{'background':'transparent','paddingTop':'0px','borderColor':'','borderStyle':'solid','borderWidth':'0px','paddingLeft':'0px','borderRadius':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'1px','borderTopRightRadius':'1px','borderBottomLeftRadius':'1px','borderBottomRightRadius':'1px'}"
      slot="r0-c0" area="r0-c0">
      <NucGroupElement bgColor="" v-bind:visibility="true" ncTooltipText="" nucalScaleWidth="0.401NS"
        nucalScaleHeight="0.655NS" position="absolute" top="16.815742397137747%" left="8.275862068965518%"
        v-bind:snapX="false" v-bind:snapY="false" id="ed8e4ddf-56f2-470f-b830-a28dce85bc45"
        v-bind:style="{'color':'#FFFFFF','fontSize':'15px','maxWidth':'','minWidth':'','tabIndex':'-1','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'center','background':'','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','lineHeight':'1.25','marginLeft':'0px','paddingTop':'5px','textShadow':'','marginRight':'0px','paddingLeft':'6px','marginBottom':'0px','paddingRight':'6px','paddingBottom':'5px','textDecoration':'none'}">
        <WSquaredPrimaryButton tag="button" v-bind:pill="false" size="md" text="Primary" type="button"
          v-bind:block="false" color="" theme="theme--light01" v-bind:squared="true" variant="primary"
          v-bind:isEnabled="true" background="" borderColor="" ncTypography="body1" v-bind:resetTrigger="false"
          ncTooltipText="" verticalWidth="60px"
          v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
          verticalHeight="60px" horizontalWidth="72.4479px" nucalScaleWidth="" horizontalHeight="37.5347px"
          ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF" nucalScaleHeight=""
          ncClickBorderColor="#4285f4" ncDisableFontColor="#FFFFFF" ncFocusBorderColor="#4285f4"
          ncHoverBorderColor="#4285f4" ncDisableBorderColor="transparent" ncClickBackgroundColor="#4285f4"
          ncFocusBackgroundColor="#4285f4" ncHoverBackgroundColor="#4285f4" ncDisableBackgroundColor="#969696"
          position="absolute" top="25.31199059351701%" left="33.67654940901013%" v-bind:snapX="false"
          v-bind:snapY="false" id="80ab697a-d4e6-44e4-aef6-76d0d3476fd9"
          v-bind:style="{'width':'','height':'','fontSize':'12px','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'center','fontFamily':'OpenSans-Bold,Open Sans','fontWeight':'bold','lineHeight':'1.4','marginLeft':'0px','paddingTop':'','textShadow':'','visibility':'visible','borderStyle':'solid','marginRight':'0px','paddingLeft':'','marginBottom':'0px','paddingRight':'','paddingBottom':'','borderTopWidth':'1px','textDecoration':'none','borderLeftWidth':'1px','borderRightWidth':'1px','horizontalHeight':'37.5347px','borderBottomWidth':'1px','borderTopLeftRadius':'4px','borderTopRightRadius':'4px','borderBottomLeftRadius':'4px','borderBottomRightRadius':'4px'}"/>
        <WSecondaryButton tag="button" v-bind:pill="false" size="md" text="Secondary" type="button" v-bind:block="false"
          color="" theme="theme--light01" v-bind:squared="false" variant="secondary" v-bind:isEnabled="true"
          background="" borderColor="" ncTypography="body1" v-bind:resetTrigger="false" ncTooltipText=""
          verticalWidth="60px"
          v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
          verticalHeight="60px" horizontalWidth="72.4479px" nucalScaleWidth="" horizontalHeight="37.5347px"
          ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF" nucalScaleHeight=""
          ncClickBorderColor="#4285f4" ncDisableFontColor="#FFFFFF" ncFocusBorderColor="#4285f4"
          ncHoverBorderColor="#4285f4" ncDisableBorderColor="transparent" ncClickBackgroundColor="#4285f4"
          ncFocusBackgroundColor="#4285f4" ncHoverBackgroundColor="#4285f4" ncDisableBackgroundColor="#969696"
          position="absolute" top="49.25576547927634%" left="31.318231826003554%" v-bind:snapX="false"
          v-bind:snapY="false" id="650cace3-4e50-4aed-b06b-0f0558d531c4"
          v-bind:style="{'width':'','height':'','fontSize':'12px','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'center','fontFamily':'OpenSans-Bold,Open Sans','fontWeight':'bold','lineHeight':'1.4','marginLeft':'0px','paddingTop':'','textShadow':'','visibility':'visible','borderStyle':'solid','marginRight':'0px','paddingLeft':'','marginBottom':'0px','paddingRight':'','paddingBottom':'','borderTopWidth':'1px','textDecoration':'none','borderLeftWidth':'1px','borderRightWidth':'1px','horizontalHeight':'37.5347px','borderBottomWidth':'1px','borderTopLeftRadius':'4px','borderTopRightRadius':'4px','borderBottomLeftRadius':'4px','borderBottomRightRadius':'4px'}"/>
        <WNumberInput id="4ccdddc9-390b-4b88-a42e-433dfa760497" v-bind:lazy="false" size="md" text=""
          v-bind:trim="false" v-bind:noWheel="false" v-bind:disabled="false" v-bind:readonly="false"
          v-bind:required="false" wordList="" v-bind:autofocus="false" v-bind:plaintext="false" background=""
          ariaInvalid="false" v-bind:debounceVal="0" ncInputType="number" placeholder="" v-bind:previewMode="true"
          autocomplete="" ncTypography="body1" v-bind:lazyFormatter="false" ncTooltipText=""
          v-bind:isWordListOpen="false"
          v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':true,'structure':[{'type':'number','ncKey':'type','ncType':{'ncInputType':'number'},'ncValue':'number','propName':'text','displayName':'Value','nsDefaultValue':'string'}]}"
          v-bind:isNumberConvert="false" nucalScaleWidth="" ncClickFontColor="#434855" ncFocusFontColor="#434855"
          ncHoverFontColor="#434855" ncMaxNumberValue="100" ncMinNumberValue="0" nucalScaleHeight=""
          ncClickBorderColor="#000000" ncDisableFontColor="#434855" ncFocusBorderColor="#000000"
          ncHoverBorderColor="#000000" ncDisableBorderColor="#000000" formatterFunctionName=""
          ncClickBackgroundColor="#ffffff" ncFocusBackgroundColor="#ffffff" ncHoverBackgroundColor="#ffffff"
          ncDisableBackgroundColor="#ffffff" position="absolute" top="68.4107853878838%" left="22.483003751868882%"
          v-bind:snapX="false" v-bind:snapY="false"
          v-bind:style="{'color':'','fontSize':'12px','maxWidth':'','minWidth':'158','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'left','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','lineHeight':'1','marginLeft':'0px','paddingTop':'0px','visibility':'visible','borderColor':'#D1D1D6','borderStyle':'solid','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'none'}"/>
        <WInput id="c2cda656-77f7-496a-bf09-9e84ef10f6f9" v-bind:lazy="false" size="md" step="" text=""
          v-bind:trim="false" v-bind:noWheel="false" v-bind:disabled="false" v-bind:readonly="false"
          v-bind:required="false" wordList="" v-bind:autofocus="false" v-bind:plaintext="false" background=""
          ariaInvalid="false" v-bind:debounceVal="0" ncInputType="text" placeholder="Enter something..."
          v-bind:previewMode="true" autocomplete="" ncTypography="body1" v-bind:lazyFormatter="false" ncTooltipText=""
          v-bind:isWordListOpen="false"
          v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':true,'structure':[{'type':'string','ncKey':'type','ncType':{'ncInputType':'number'},'ncValue':'number','propName':'text','displayName':'Value','nsDefaultValue':'string'}]}"
          v-bind:isNumberConvert="false" nucalScaleWidth="" ncClickFontColor="#434855" ncFocusFontColor="#434855"
          ncHoverFontColor="#434855" ncMaxNumberValue="100" ncMinNumberValue="0" nucalScaleHeight=""
          ncClickBorderColor="#000000" ncDisableFontColor="#434855" ncFocusBorderColor="#000000"
          ncHoverBorderColor="#000000" ncDisableBorderColor="#000000" formatterFunctionName=""
          ncClickBackgroundColor="#ffffff" ncFocusBackgroundColor="#ffffff" ncHoverBackgroundColor="#ffffff"
          ncDisableBackgroundColor="#ffffff" position="absolute" top="84.82937388097592%" left="26.624164292363677%"
          v-bind:snapX="false" v-bind:snapY="false"
          v-bind:style="{'color':'','fontSize':'12px','maxWidth':'','minWidth':'158px','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'left','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','lineHeight':'1','marginLeft':'0px','paddingTop':'0px','visibility':'visible','borderColor':'#D1D1D6','borderStyle':'solid','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'none'}"/>
      </NucGroupElement>
    </NucGridCell>
  </NucGridPage>
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

<style scoped></style>
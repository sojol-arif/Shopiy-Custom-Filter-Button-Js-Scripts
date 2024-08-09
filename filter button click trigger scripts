// This script for button filter click show only his element
// Collection Form click auto bind and bind to form
/* Shopify filter url: https://shopify.dev/docs/storefronts/themes/navigation-search/filtering/storefront-filtering/support-storefront-filtering */

function clickBindCollectionFilter(){

    const allCollectionProductType = document.querySelectorAll('.custom-collection-product-type-filter-wrapper ul li');
    //All Element Trigger Click For Reset
    allCollectionProductType.forEach(onClickTriggerReset);
    //Each element triger click to form
    allCollectionProductType.forEach(onClickTrigger);
  
    function onClickTrigger(element){
       element.onclick = function(){
         
           //Form submit trigger
           document.querySelector('#custom-filter-product-type-form').submit();
       };
    }
   
    function onClickTriggerReset(element){
         if(element.querySelector('label input').checked){
            element.querySelector('label').click();
         }
    }
}

<template>
    <div class="family-inter bg-[#F4F9FD]">

      <!-- header section start here -->
      <header class="w-full bg-gradient h-[56px]">
        <div class="h-full max-w-screen-2xl mx-auto md:px-7 px-3.5 flex items-center justify-between">
            <div class="mr-3.5 sm:mr-0">
                <img class="hidden sm:block" src="~/assets/images/budget--logo.svg" width="122" height="26" alt="Logo">
                <img class="sm:hidden" src="~/assets/images/budget-favicon.svg" width="28" height="19" alt="Logo">
            </div>
            <div class="flex items-center h-full">
                <div class="relative border-l border-r border-[#3C6DA7] h-full md:w-[280px] w-full">
                    <input type="text" class="px-6 py-3 w-full text-[17px] text-gray-200 font-medium h-full bg-transparent focus:outline-none placeholder-[#7192B5]" placeholder="Search..." name="" id="">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-[#ABCDF0] absolute top-3.5 right-5" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" />
                    </svg>
                </div>
                <div class="h-full flex items-center md:ml-7 ml-3.5 cursor-pointer">
                    <div>
                        <img class="rounded-full" src="https://images.unsplash.com/photo-1633332755192-727a05c4013d?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MjR8fG1hbnxlbnwwfDJ8MHx8&auto=format&fit=crop&w=500&q=60" width="28" height="28" alt="User">
                    </div>
                    <div class="pl-4 hidden md:block">
                        <span class="text-sm font-semibold text-white">Mr. John Smith</span>
                    </div>
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-7 w-7 md:ml-12 ml-1.5 text-white" viewBox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd" d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z" clip-rule="evenodd" />
                    </svg>
                </div>
            </div>
        </div>
    </header>
    <!-- header section end here -->


    <!-- main section start here -->
    <main class="max-w-screen-2xl mx-auto md:px-8 px-3.5 md:py-[27px] py-3">
        <div class="md:flex items-center md:justify-between">
            <div class="ml-2">
              <div class="flex items-center space-x-2 justify-end mb-3.5 md:mb-0">
                <button class="md:px-7 sm:px-4 px-3 py-3.5 md:text-[15px] text-xs font-medium uppercase text-white bg-[#4990E2] rounded-md shadow-md">PEER COMPARISION</button>
                <button class="md:px-7 sm:px-4 px-3 py-2 md:text-[15px] text-xs font-medium uppercase text-white bg-[#4990E2] rounded-md shadow-md flex items-center">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-7 w-7" viewBox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-11a1 1 0 10-2 0v2H7a1 1 0 100 2h2v2a1 1 0 102 0v-2h2a1 1 0 100-2h-2V7z" clip-rule="evenodd" />
                    </svg>
                    <span class="ml-2">create company</span>
                </button>
            </div>
            </div>
            <div class="relative w-full md:w-[36%] order-first">
                <input type="text" class="w-full text-base font-normal pl-10 pr-4 rounded-md border border-[#89AFEE] py-2.5 bg-transparent focus:outline-none" placeholder="Search by company name">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-[#75A9E2] absolute top-3 left-3" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" />
                </svg>
            </div>
        </div>
        <div class="mt-[23px] border border-[#ACCDF0] rounded-md">
            <div class="flex flex-col">
                <div class="overflow-x-auto">
                    <div class="align-middle inline-block min-w-full">
                        <div class="shadow overflow-hidden border-b border-gray-200 sm:rounded-md">
                            <table class="min-w-full divide-y divide-gray-200 whitespace-nowrap">
                                <thead class="bg-[#ACCDF0]">
                                    <tr>
                                        <th scope="col" class="px-2.5 py-3 text-left text-[15px] font-semibold">Id</th>
                                        <th scope="col" class="md:px-6 px-2 py-3 text-left text-[15px] font-semibold">Company Name</th>
                                        <th scope="col" class="md:px-6 px-2 py-3 text-left text-[15px] font-semibold">Files Processed</th>
                                        <th scope="col" class="md:px-6 px-2 py-3 text-left text-[15px] font-semibold">Last Reported Period</th>
                                        <th scope="col" class="md:px-6 px-2 py-3 text-left text-[15px] font-semibold">
                                            <div class="flex items-center space-x-1">
                                                <span>Last File Processing Date</span>
                                                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                                                    <path stroke-linecap="round" stroke-linejoin="round" d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z" />
                                                </svg>
                                            </div>
                                        </th>
                                        <th scope="col" class="md:px-6 px-2 py-3 text-left text-[15px] font-semibold">Sector</th>
                                        <th scope="col" class="md:px-6 px-2 py-3 text-left text-[15px] font-semibold">Country</th>
                                        <th scope="col" class="px-2.5 py-3 text-right text-[15px] font-semibold">Actions</th>
                                    </tr>
                                </thead>
                                <tbody v-for="(item, index) in tableData" class="bg-white divide-y divide-gray-200">
                                    <tr :class="{'bg-[#F4F9FD] font-semibold' : item.openAccordion, 'font-normal' : !item.openAccordion}">
                                      <td class="px-2.5 py-3.5 whitespace-nowrap">
                                          <div class="text-[15px] text-gray-900">{{item.id}}</div>
                                      </td>
                                      <td class="md:px-6 px-2 py-3.5 whitespace-nowrap">
                                          <div @click="item.openAccordion = !item.openAccordion" class="flex items-center gap-1.5 cursor-pointer hover:text-blue-600">
                                              <svg xmlns="http://www.w3.org/2000/svg" :class="{'hidden' : item.openAccordion, 'block' : !item.openAccordion}" class="h-6 w-6 text-[#8AB0F1]" viewBox="0 0 20 20" fill="currentColor"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-11a1 1 0 10-2 0v2H7a1 1 0 100 2h2v2a1 1 0 102 0v-2h2a1 1 0 100-2h-2V7z" clip-rule="evenodd" /></svg>
                                              <svg xmlns="http://www.w3.org/2000/svg" :class="{'block' : item.openAccordion, 'hidden' : !item.openAccordion}" class="h-6 w-6 text-gray-900" viewBox="0 0 20 20" fill="currentColor"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zM7 9a1 1 0 000 2h6a1 1 0 100-2H7z" clip-rule="evenodd" /></svg>
                                              <div class="text-[15px] text-gray-900">{{item.company_name}}</div>
                                          </div>
                                      </td>
                                      <td class="md:px-6 px-2 py-3.5 whitespace-nowrap"><div class="text-[15px]  text-gray-900">{{item.files_processed}}</div></td>
                                      <td class="md:px-6 px-2 py-3.5 whitespace-nowrap"><div class="text-[15px] text-gray-900">{{item.last_reported}}</div></td>
                                      <td class="md:px-6 px-2 py-3.5 whitespace-nowrap"><div class="text-[15px] text-gray-900">{{item.processing_date}}</div></td>
                                      <td class="md:px-6 px-2 py-3.5 whitespace-nowrap"><div class="text-[15px] text-gray-900">{{item.sector}}</div></td>
                                      <td class="md:px-6 px-2 py-3.5 whitespace-nowrap"><div class="text-[15px] text-gray-900">{{item.country}}</div></td>
                                      <td class="md:px-6 px-2 py-3.5 whitespace-nowrap"><svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-[#4B8FE1] mx-auto" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2"><path stroke-linecap="round" stroke-linejoin="round" d="M5 12h.01M12 12h.01M19 12h.01M6 12a1 1 0 11-2 0 1 1 0 012 0zm7 0a1 1 0 11-2 0 1 1 0 012 0zm7 0a1 1 0 11-2 0 1 1 0 012 0z" /></svg></td>
                                    </tr>
                                    <tr v-if="item.openAccordion">
                                      <td colspan="8" class="md:px-6 px-2 py-3.5 bg-[#F4F9FD]">
                                        <div class="border-[1.5px] border-[#ACCDF0] bg-white">
                                          <div class="p-2.5 border-b border-[#ACCDF0] flex justify-between items-center">
                                            <h3 class="text-[15px] font-semibold text-gray-900">ISIN: <span class="font-medium">US88579Y1010</span></h3>
                                            <h3 class="text-[15px] font-semibold text-gray-900">Currency: <span class="font-medium">USD</span></h3>
                                          </div>
                                    
                                          <div class="flex flex-col">
                                            <div class="overflow-x-auto">
                                              <div class="align-middle inline-block min-w-full">
                                                  <div class="shadow overflow-hidden border-b border-gray-200 sm:rounded-md">
                                                      <table class="min-w-full divide-y divide-gray-200">
                                                          <thead class="bg-white">
                                                              <tr>
                                                                  <th scope="col" class="px-2.5 py-3 text-left text-[15px] font-semibold">Document Id</th>
                                                                  <th scope="col" class="md:px-6 px-2 py-3 text-left text-[15px] font-semibold">Name of Filing</th>
                                                                  <th scope="col" class="md:px-6 px-2 py-3 text-left text-[15px] font-semibold">Period Name</th>
                                                                  <th scope="col" class="md:px-6 px-2 py-3 text-left text-[15px] font-semibold">Reported Date</th>
                                                                  <th scope="col" class="md:px-6 px-2 py-3 text-left text-[15px] font-semibold">Processed By</th>
                                                                  <th scope="col" class="md:px-6 px-2 py-3 text-left text-[15px] font-semibold">Processed Date</th>
                                                                  <th scope="col" class="px-2.5 py-3 text-center text-[15px] font-semibold">Status</th>
                                                              </tr>
                                                          </thead>
                                                          <tbody class="bg-white divide-y divide-gray-200">
                                                              <tr v-for="(ele, index) in item.subTableData">
                                                                  <td class="px-2.5 py-3.5 whitespace-nowrap">
                                                                      <div class="text-[15px] font-normal text-gray-900">{{ele.id}}</div>
                                                                  </td>
                                                                  <td class="md:px-6 px-2 py-1.5 whitespace-nowrap"><div class="text-[15px] font-normal text-gray-900">{{ele.filing}}</div></td>
                                                                  <td class="md:px-6 px-2 py-1.5 whitespace-nowrap"><div class="text-[15px] font-normal text-gray-900">{{ele.period_name}}</div></td>
                                                                  <td class="md:px-6 px-2 py-1.5 whitespace-nowrap"><div class="text-[15px] font-normal text-gray-900">{{ele.reported_date}}</div></td>
                                                                  <td class="md:px-6 px-2 py-1.5 whitespace-nowrap"><div class="text-[15px] font-normal text-gray-900">{{ele.processed_by}}</div></td>
                                                                  <td class="md:px-6 px-2 py-1.5 whitespace-nowrap"><div class="text-[15px] font-normal text-gray-900">{{ele.processed_date}}</div></td>
                                                                  <td class="px-2.5 py-1.5 whitespace-nowrap"><div class="flex justify-end"><button class="bg-[#5194E3] px-4 py-2.5 rounded text-white font-medium text-xs">Reprocess</button></div></td>                        
                                                              </tr>
                                                          </tbody>
                                                      </table>
                                                  </div>
                                              </div>
                                            </div>
                                            <div class="flex justify-end px-2.5 py-2">
                                              <a href="#" class="text-blue-500 flex">
                                                <span class="text-sm font-medium mr-2">View All</span>
                                                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                                                  <path stroke-linecap="round" stroke-linejoin="round" d="M14 5l7 7m0 0l-7 7m7-7H3" />
                                                </svg>
                                              </a>
                                            </div>
                                          </div>
                                          </div>
                                        </td>
                                    </tr>
                                </tbody>
                            </table>
                        </div>
                    </div>
                </div>
              </div>
        </div>
    </main>
    <!-- main section end here -->
    
    
    <!-- footer section start here -->
    <footer class="w-full bg-white h-[32px] border-t border-[#ACCDF0]">
        <div class="h-full max-w-screen-2xl mx-auto px-7 sm:flex items-center justify-between">
            <span class="text-[13px] text-[#414141] mr-2">Copyright © 2022. All Rights Reserved</span>
            <span class="text-[13px] text-[#414141]">Powered by : StarRocket</span>
        </div>
    </footer>
    <!-- footer section end here -->
    </div>
</template>

<script>
export default {
  name: 'IndexPage',
  data(){
    return{
      openAccordion:false,
      tableData:[
        {id:"12634", company_name:"K+S AG", files_processed:'12', last_reported:'2018FY', processing_date:'2022-03-12T00:00:00', sector:'Standard', country:'US', openAccordion:false, subTableData:[
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
          ] 
        },
        {id:"12712", company_name:"La Mondiale", files_processed:'12', last_reported:'2018FY', processing_date:'2022-03-12T00:00:00', sector:'Standard', country:'US', openAccordion:false, subTableData:[
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
          ]
        },
        {id:"12627", company_name:"Syngenta Ag", files_processed:'12', last_reported:'2018FY', processing_date:'2022-03-12T00:00:00', sector:'Standard', country:'US', openAccordion:false, subTableData:[
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
          ]
        },
        {id:"11097", company_name:"361 Degrees International", files_processed:'12', last_reported:'2018FY', processing_date:'2022-03-12T00:00:00', sector:'Standard', country:'US', openAccordion:false, subTableData:[
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
          ]
        },
        {id:"10489", company_name:"3M Company", files_processed:'12', last_reported:'2018FY', processing_date:'2022-03-12T00:00:00', sector:'Standard', country:'US', openAccordion:true, subTableData:[
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
          ]
        },
        {id:"12634", company_name:"K+S AG", files_processed:'12', last_reported:'2018FY', processing_date:'2022-03-12T00:00:00', sector:'Standard', country:'US', openAccordion:false, subTableData:[
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
          ]
        },
        {id:"12712", company_name:"La Mondiale", files_processed:'12', last_reported:'2018FY', processing_date:'2022-03-12T00:00:00', sector:'Standard', country:'US', openAccordion:false, subTableData:[
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
          ]
        },
        {id:"12627", company_name:"Syngenta Ag", files_processed:'12', last_reported:'2018FY', processing_date:'2022-03-12T00:00:00', sector:'Standard', country:'US', openAccordion:false, subTableData:[
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
          ]
        },
        {id:"11097", company_name:"361 Degrees International", files_processed:'12', last_reported:'2018FY', processing_date:'2022-03-12T00:00:00', sector:'Standard', country:'US', openAccordion:false, subTableData:[
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
          ]
        },
        {id:"10489", company_name:"3M Company", files_processed:'12', last_reported:'2018FY', processing_date:'2022-03-12T00:00:00', sector:'Standard', country:'US', openAccordion:false, subTableData:[
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
            {id:'39054', filing:'32548_ABGDC_98745632...', period_name:'2021Q2', reported_date:'2020-02-28T00:00:00', processed_by:'autoGeneratedId@gmail.com', processed_date:'2020-02-28T00:00:00'},
          ]
        },
      ],
      
    }
  }
}
</script>

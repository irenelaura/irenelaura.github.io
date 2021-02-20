+++
title = "Busque la llanta que necesita"
description = "Tenemos la llanta que busca!"
author = "Llanty Par San Francisco"
tags = ["shortcodes", "privacy"]
[[images]]
  src = "img/2019/03/image.jpg"
  alt = "llantas"
  stretch = "Vertical"
+++
 
 <section class="buscador_llantas section-sm col-lg-12 col-12 mt-0" id=buscador_marcas>
        <div class=container>
            <div class="row d-flex flex-wrap justify-content-center">
                <div class="titulo-llantas col-lg-6 mx-auto text-center mb-5 mt-5">
                    <h2>LLantas</h2>
                </div>
            </div>
            <div class="buscador col-lg-4 col-md-6 order-1 order-md-1 order-lg-1 float-left">
                <div class="jumbotron text-center p-3">
                    <h3>Encuentre su llanta</h3><img src=/recursos/search_rin.webp class="mx-auto my-2 col-10 d-block"
                        loading=lazy>
                    <div>
                        <div class="form-group d-flex flex-wrap col-12 m-0 p-0"><label
                                class="mx-auto my-3 p-0 pr-1 col-12"><strong>Tipo de Vehículo</strong>
                                <select class="custom-select mt-1" required id=vehicle-select
                                    onchange=onVehicleSelectChanged()>
                                    <option value=car>Auto y Camioneta</option>
                                </select></label>
                            <label class="col-lg-4 p-0 pr-1"><strong>Ancho</strong>
                                <select class=custom-select required id=width-select onchange=onWidthSelectChanged()>
                                    <option>155</option>
                                    <option>165</option>
                                    <option>175</option>
                                    <option>185</option>
                                    <option>195</option>
                                    <option>205</option>
                                    <option>215</option>
                                    <option>225</option>
                                    <option>235</option>
                                    <option>245</option>
                                    <option>255</option>
                                    <option>265</option>
                                    <option>275</option>
                                    <option>28</option>
                                    <option>285</option>
                                    <option>295</option>
                                    <option>30</option>
                                    <option>305</option>
                                    <option>31</option>
                                    <option>315</option>
                                    <option>32</option>
                                    <option>325</option>
                                    <option>33</option>
                                    <option>34</option>
                                    <option>35</option>
                                    <option>37</option>
                                </select></label>
                            <label class="col-lg-4 p-0 pr-1"><strong>Alto</strong>
                                <select class=custom-select required id=height-select onchange=onHeightSelectChanged()>
                                    <option>0</option>
                                    <option>10</option>
                                    <option>10.5</option>
                                    <option>12.5</option>
                                    <option>25</option>
                                    <option>30</option>
                                    <option>35</option>
                                    <option>40</option>
                                    <option>45</option>
                                    <option>50</option>
                                    <option>55</option>
                                    <option>60</option>
                                    <option>65</option>
                                    <option>70</option>
                                    <option>75</option>
                                    <option>80</option>
                                    <option>85</option>
                                    <option>9.5</option>
                                </select></label>
                            <label class="col-lg-4 p-0 pr-1"><strong>Rin</strong>
                                <select class=custom-select required id=rin-select onchange=onRinSelectChanged()>
                                    <option>R13</option>
                                    <option>R14</option>
                                    <option>R15</option>
                                    <option>R16</option>
                                    <option>R17</option>
                                    <option>R18</option>
                                    <option>R19</option>
                                    <option>R20</option>
                                    <option>R21</option>
                                    <option>R22</option>
                                    <option>R27</option>
                                </select></label>
                            <button class="btn btn-primary mx-auto my-3 col-12" onclick=onSearchFormSubmit() disabled
                                id=btn-tires-form>
                                Buscar</button>
                        </div>
                    </div><a class="align-items-center text-left row mt-1 col" href=/leer-tamano-de-llanta
                        title="Cómo identificar el tamaño de sus llantas?"><i class=ti-help-alt
                            style=font-size:18px!important></i>
                        <div class=col>Cómo identificar el tamaño de sus llantas?</div>
                    </a>
                </div>
                <script>const validSizes = new Set(["car_195_80_R14", "car_195_80_R15", "car_215_65_R15", "car_225_75_R16", "car_215_85_R16", "car_235_85_R16", "car_245_70_R17", "car_245_75_R16", "car_195_75_R16", "car_245_75_R16", "car_285_60_R18", "car_235_55_R19", "car_235_55_R19", "car_235_60_R18", "car_245_45_R20", "car_255_45_R20", "car_255_45_R20", "car_255_50_R19", "car_255_50_R19", "car_265_50_R19", "car_275_45_R20", "car_275_45_R20", "car_275_55_R17", "car_235_60_R18", "car_235_60_R18", "car_245_45_R20", "car_255_55_R18", "car_275_40_R20", "car_225_75_R16", "car_245_75_R17", "car_275_70_R18", "car_285_55_R20", "car_285_65_R18", "car_265_70_R17", "car_275_60_R20", "car_245_50_R17", "car_195_45_R16", "car_205_45_R17", "car_215_45_R16", "car_215_45_R18", "car_225_40_R18", "car_225_40_R19", "car_225_45_R18", "car_235_40_R18", "car_245_35_R20", "car_245_35_R18", "car_245_40_R18", "car_245_45_R19", "car_255_35_R18", "car_255_35_R19", "car_255_35_R19", "car_255_40_R18", "car_255_40_R19", "car_255_40_R19", "car_255_40_R20", "car_275_40_R19", "car_285_35_R18", "car_205_40_R18", "car_205_45_R17", "car_205_55_R16", "car_215_40_R18", "car_215_45_R17", "car_215_45_R18", "car_225_35_R19", "car_225_35_R20", "car_225_40_R18", "car_225_40_R19", "car_225_45_R17", "car_225_45_R18", "car_225_45_R18", "car_225_45_R17", "car_225_45_R18", "car_225_50_R17", "car_235_35_R19", "car_235_40_R18", "car_235_40_R20", "car_235_45_R18", "car_245_35_R18", "car_245_35_R19", "car_245_35_R20", "car_245_40_R18", "car_245_40_R18", "car_245_40_R19", "car_245_40_R20", "car_245_45_R18", "car_245_45_R19", "car_255_35_R19", "car_255_35_R18", "car_255_40_R18", "car_255_40_R19", "car_255_40_R20", "car_255_45_R19", "car_255_45_R18", "car_255_45_R20", "car_265_35_R18", "car_265_40_R19", "car_265_40_R21", "car_275_35_R18", "car_275_35_R20", "car_275_40_R20", "car_285_35_R18", "car_295_30_R20", "car_225_55_R19", "car_225_60_R18", "car_225_65_R17", "car_235_50_R19", "car_235_55_R19", "car_235_60_R18", "car_235_65_R18", "car_245_50_R20", "car_255_45_R20", "car_255_50_R19", "car_255_50_R20", "car_255_55_R18", "car_255_55_R19", "car_255_55_R20", "car_255_60_R18", "car_265_40_R21", "car_265_45_R20", "car_265_50_R19", "car_265_50_R20", "car_275_40_R20", "car_275_45_R20", "car_275_45_R21", "car_275_50_R21", "car_275_55_R19", "car_285_40_R21", "car_295_35_R21", "car_295_40_R20", "car_295_40_R21", "car_235_35_R20", "car_235_40_R19", "car_235_45_R20", "car_245_35_R19", "car_245_35_R20", "car_245_45_R18", "car_265_30_R20", "car_265_35_R18", "car_265_35_R19", "car_265_35_R20", "car_275_30_R20", "car_275_35_R20", "car_275_40_R19", "car_275_40_R22", "car_295_30_R20", "car_295_35_R21", "car_305_30_R20", "car_255_55_R19", "car_275_45_R20", "car_245_45_R17", "car_285_40_R18", "car_215_45_R17", "car_235_35_R19", "car_245_35_R19", "car_245_35_R20", "car_245_35_R18", "car_245_35_R20", "car_245_35_R20", "car_255_35_R19", "car_265_35_R19", "car_275_35_R19", "car_285_30_R20", "car_295_30_R20", "car_305_30_R20", "car_225_40_R18", "car_245_40_R18", "car_245_40_R19", "car_305_30_R21", "car_205_50_R17", "car_225_40_R18", "car_225_45_R17", "car_235_40_R18", "car_235_50_R17", "car_245_35_R18", "car_245_35_R19", "car_255_40_R19", "car_265_35_R19", "car_265_35_R18", "car_265_40_R18", "car_275_35_R18", "car_285_30_R18", "car_295_30_R18", "car_295_30_R18", "car_295_35_R18", "car_305_35_R20", "car_225_35_R19", "car_225_40_R18", "car_225_40_R18", "car_225_40_R18", "car_225_45_R18", "car_235_35_R19", "car_245_35_R20", "car_245_35_R18", "car_245_35_R19", "car_245_35_R20", "car_245_40_R21", "car_245_40_R20", "car_255_30_R19", "car_255_35_R18", "car_255_35_R19", "car_255_35_R20", "car_255_40_R18", "car_255_40_R18", "car_255_40_R20", "car_255_45_R19", "car_265_30_R20", "car_265_35_R19", "car_265_35_R19", "car_265_35_R22", "car_265_40_R18", "car_265_40_R19", "car_275_35_R21", "car_275_35_R20", "car_275_40_R18", "car_285_30_R20", "car_285_35_R18", "car_295_30_R20", "car_295_35_R19", "car_295_35_R19", "car_295_35_R20", "car_305_30_R20", "car_285_35_R19", "car_255_60_R19", "car_205_55_R17", "car_235_55_R18", "car_245_50_R18", "car_205_50_R17", "car_245_40_R17", "car_265_65_R18", "car_275_65_R18", "car_235_80_R17", "truck_215_85_R16", "truck_235_85_R16", "truck_215_85_R16", "car_235_70_R16", "car_235_75_R15", "car_255_70_R16", "car_265_70_R16", "car_265_70_R17", "car_31_10.5_R15", "car_265_75_R16", "car_285_75_R16", "car_215_75_R15", "car_235_65_R17", "car_235_75_R16", "car_265_75_R16", "car_225_65_R17", "car_225_70_R16", "car_225_75_R16", "car_235_65_R18", "car_235_70_R16", "car_245_55_R19", "car_245_65_R17", "car_245_70_R16", "car_245_75_R16", "car_265_65_R17", "car_265_70_R16", "car_265_70_R17", "car_275_55_R20", "car_215_70_R16", "car_225_70_R15", "car_235_60_R17", "car_235_60_R18", "car_235_70_R15", "car_245_50_R20", "car_225_75_R16", "car_215_85_R16", "car_225_75_R16", "car_235_85_R16", "car_245_75_R16", "car_185_0_R14", "car_205_55_R16", "car_215_55_R16", "car_275_40_R18", "car_175_65_R14", "car_175_65_R15", "car_185_55_R16", "car_185_60_R14", "car_185_60_R15", "car_185_65_R14", "car_195_55_R15", "car_195_55_R16", "car_195_60_R14", "car_205_50_R17", "car_205_55_R16", "car_205_60_R15", "car_205_60_R16", "car_205_60_R16", "car_205_70_R15", "car_215_50_R17", "car_215_55_R17", "car_215_60_R15", "car_215_60_R16", "car_215_60_R17", "car_215_70_R15", "car_215_70_R16", "car_225_40_R18", "car_225_45_R17", "car_225_50_R17", "car_225_55_R17", "car_225_55_R18", "car_225_60_R15", "car_225_60_R17", "car_225_60_R18", "car_225_65_R16", "car_225_65_R17", "car_235_45_R18", "car_235_55_R18", "car_235_60_R17", "car_235_65_R16", "car_245_50_R17", "car_275_55_R20", "car_155_80_R13", "car_175_70_R14", "car_185_70_R14", "car_185_75_R14", "car_195_70_R14", "car_195_75_R14", "car_205_70_R14", "car_205_75_R14", "car_205_75_R15", "car_215_65_R15", "car_215_70_R14", "car_155_80_R15", "car_185_70_R13", "car_165_70_R14", "car_175_65_R14", "car_175_70_R13", "car_175_70_R14", "car_185_55_R15", "car_185_60_R14", "car_185_60_R15", "car_185_65_R14", "car_185_65_R15", "car_185_70_R14", "car_195_50_R15", "car_195_55_R15", "car_195_60_R15", "car_195_65_R15", "car_195_70_R14", "car_205_55_R16", "car_205_60_R16", "car_205_65_R15", "car_215_55_R17", "car_215_60_R16", "car_225_45_R17", "car_225_50_R17", "car_205_50_R17", "car_205_60_R15", "car_215_50_R17", "car_215_55_R16", "car_215_55_R18", "car_215_60_R16", "car_215_60_R17", "car_225_45_R18", "car_225_55_R17", "car_225_55_R18", "car_225_60_R18", "car_225_60_R17", "car_225_60_R18", "car_225_65_R16", "car_235_45_R18", "car_235_55_R17", "car_235_60_R16", "car_235_65_R16", "car_215_70_R16", "car_225_55_R19", "car_225_70_R16", "car_225_75_R16", "car_235_55_R18", "car_235_55_R19", "car_235_60_R18", "car_235_65_R17", "car_235_65_R18", "car_235_70_R16", "car_245_50_R20", "car_245_55_R19", "car_245_60_R18", "car_245_70_R17", "car_245_75_R16", "car_255_50_R20", "car_255_55_R18", "car_255_60_R19", "car_255_65_R17", "car_255_70_R16", "car_265_65_R18", "car_265_70_R17", "car_275_55_R20", "car_205_70_R15", "car_215_65_R15", "car_215_70_R15", "car_215_70_R16", "car_225_65_R17", "car_235_60_R17", "car_235_70_R15", "car_235_75_R15", "car_255_70_R15", "car_265_60_R18", "car_265_65_R17", "car_265_70_R16", "car_235_85_R16", "car_245_75_R16", "car_265_70_R17", "car_265_70_R17", "car_265_70_R18", "car_265_75_R16", "car_30_9.5_R15", "car_315_75_R16", "car_31_10.5_R15", "car_33_12.5_R15", "car_33_12.5_R20", "car_34_10.5_R17", "car_35_12.5_R15", "car_35_12.5_R17", "car_35_12.5_R18", "car_35_12.5_R20", "car_215_65_R16", "car_215_70_R16", "car_215_75_R15", "car_225_65_R17", "car_225_70_R16", "car_225_75_R16", "car_235_70_R16", "car_235_75_R15", "car_235_80_R17", "car_245_70_R16", "car_245_70_R17", "car_245_75_R17", "car_255_55_R18", "car_255_65_R17", "car_255_70_R16", "car_255_70_R17", "car_255_75_R17", "car_265_65_R17", "car_265_65_R18", "car_265_70_R16", "car_275_60_R20", "car_275_65_R17", "car_275_65_R18", "car_275_65_R20", "car_275_70_R16", "car_275_70_R17", "car_285_60_R18", "car_285_65_R18", "car_285_70_R17", "car_285_75_R16", "car_295_75_R16", "car_305_55_R20", "car_305_65_R17", "car_305_70_R16", "car_315_70_R17", "car_325_65_R18", "car_37_12.5_R17", "car_235_80_R17", "car_235_85_R16", "car_245_70_R17", "car_215_85_R16", "car_225_75_R16", "car_245_75_R16", "car_245_75_R17", "car_265_70_R17", "car_205_50_R15", "car_195_55_R15", "car_205_45_R17", "car_205_45_R16", "car_205_50_R16", "car_205_50_R17", "car_205_55_R16", "car_215_40_R18", "car_215_45_R17", "car_215_50_R17", "car_225_40_R18", "car_225_45_R27", "car_225_50_R17", "car_235_45_R17", "car_235_45_R18", "car_235_50_R18", "car_245_40_R18", "car_245_40_R19", "car_245_45_R17", "car_245_45_R18", "car_245_45_R20", "car_255_35_R19", "car_255_40_R18", "car_255_45_R17", "car_275_40_R19", "car_32_10_R15", "car_33_10.5_R15", "car_33_12.5_R17", "car_33_12.5_R18", "car_33_12.5_R15", "car_35_12.5_R17", "car_215_75_R15", "car_225_75_R16", "car_235_70_R16", "car_235_85_R16", "car_245_65_R17", "car_245_70_R17", "car_245_75_R16", "car_245_75_R17", "car_255_70_R16", "car_255_75_R17", "car_265_60_R18", "car_265_65_R17", "car_265_70_R16", "car_265_75_R16", "car_275_70_R18", "car_285_55_R20", "car_285_65_R18", "car_285_70_R18", "car_285_75_R16", "car_285_75_R16", "car_305_55_R20", "car_305_70_R16", "car_315_75_R16", "car_325_60_R20", "car_325_65_R18", "car_28_10_R14", "car_30_10_R14", "car_30_10_R15", "car_32_10_R14", "car_225_70_R15", "car_245_60_R14", "car_155_80_R15", "car_205_60_R13", "car_205_60_R15", "car_205_70_R14", "car_215_60_R14", "car_215_60_R15", "car_215_70_R14", "car_215_70_R15", "car_225_60_R15", "car_235_60_R14", "car_235_60_R15", "car_235_70_R15", "car_245_60_R15", "car_255_60_R15", "car_255_70_R15", "car_275_60_R15", "car_295_50_R15", "car_185_70_R13", "car_175_65_R14", "car_185_75_R16", "car_185_0_R14", "car_195_70_R15", "car_195_0_R15", "car_205_65_R15", "car_205_70_R15", "car_205_75_R14", "car_215_70_R16", "car_215_75_R16", "car_225_70_R15", "car_225_75_R16", "car_215_50_R17", "car_215_75_R15", "car_225_55_R17", "car_235_70_R16", "car_235_75_R15", "car_245_65_R17", "car_245_70_R16", "car_255_50_R20", "car_255_55_R20", "car_255_65_R16", "car_255_65_R18", "car_255_70_R16", "car_255_70_R17", "car_255_75_R17", "car_265_65_R17", "car_265_65_R18", "car_265_70_R16", "car_265_75_R16", "car_275_55_R20", "car_275_60_R20", "car_285_45_R22", "car_225_75_R17", "car_245_75_R17", "car_265_70_R17", "car_265_70_R18", "car_275_65_R18", "car_275_65_R20", "car_275_70_R18", "car_285_70_R17", "car_285_75_R16", "car_235_65_R16", "car_195_60_R16", "car_165_65_R15", "car_185_60_R15", "car_175_70_R13", "car_175_80_R14", "car_195_55_R15", "car_205_65_R15", "car_155_70_R13", "car_165_65_R14", "car_165_70_R14", "car_175_65_R14", "car_175_65_R15", "car_175_70_R14", "car_185_55_R15", "car_185_55_R16", "car_185_60_R14", "car_185_60_R15", "car_185_65_R14", "car_185_65_R15", "car_185_70_R13", "car_185_70_R14", "car_195_55_R15", "car_195_60_R14", "car_195_60_R15", "car_195_70_R14", "car_205_55_R16", "car_205_60_R15", "car_215_65_R15", "car_245_45_R20", "car_275_45_R20", "car_275_55_R19", "car_295_35_R21", "car_235_55_R18", "car_235_60_R17", "car_235_60_R18", "car_235_65_R17", "car_255_45_R20", "car_255_45_R20", "car_255_55_R18", "car_255_55_R18", "car_255_55_R19", "car_255_60_R17", "car_265_40_R21", "car_265_45_R20", "car_275_40_R20", "car_275_45_R19", "car_275_50_R20", "car_275_50_R19", "car_285_40_R20", "car_295_35_R21", "car_295_35_R21", "car_295_35_R21", "car_315_40_R21", "car_225_65_R17", "car_235_55_R19", "car_235_60_R18", "car_235_65_R18", "car_255_50_R20", "car_265_60_R18", "car_235_55_R18", "car_235_80_R17", "car_245_75_R16", "car_265_70_R17", "car_275_65_R20", "car_205_60_R16", "car_205_65_R15", "car_205_70_R15", "car_215_65_R16", "car_215_75_R15", "car_225_65_R17", "car_235_70_R16", "car_235_75_R15", "car_245_65_R17", "car_245_70_R16", "car_255_70_R16", "car_265_60_R18", "car_265_65_R17", "car_265_70_R16", "car_285_65_R17", "car_245_70_R17", "car_245_75_R17", "car_275_55_R20", "car_255_70_R18", "car_245_50_R18", "car_205_50_R16", "car_205_40_R17", "car_225_50_R17", "car_225_55_R17", "car_235_45_R17", "car_245_45_R17", "car_245_45_R19", "car_255_30_R19", "car_295_25_R20", "car_225_50_R18", "car_235_50_R18", "car_295_35_R19", "car_245_35_R19", "car_305_30_R19", "car_315_35_R20", "car_225_65_R16", "car_225_60_R18", "car_225_70_R16", "car_235_45_R19", "car_275_40_R21", "car_275_45_R20", "car_275_45_R22", "car_195_55_R16", "car_205_45_R17", "car_205_55_R16", "car_205_65_R16", "car_215_50_R18", "car_215_55_R18", "car_215_65_R17", "car_225_45_R18", "car_225_45_R18", "car_225_55_R17", "car_225_55_R18", "car_225_60_R16", "car_225_60_R17", "car_235_50_R17", "car_245_40_R18", "car_245_40_R19", "car_245_45_R18", "car_245_45_R18", "car_245_45_R18", "car_245_45_R19", "car_245_45_R19", "car_245_50_R18", "car_245_55_R17", "car_275_35_R19", "car_275_40_R18", "car_275_40_R19", "car_195_55_R16", "car_195_65_R15", "car_205_50_R17", "car_205_55_R16", "car_205_55_R16", "car_205_60_R16", "car_215_50_R17", "car_215_55_R16", "car_215_55_R17", "car_215_55_R17", "car_215_60_R16", "car_215_60_R17", "car_225_45_R17", "car_225_45_R18", "car_225_50_R16", "car_225_50_R17", "car_225_50_R17", "car_225_50_R18", "car_225_55_R17", "car_225_60_R17", "car_225_60_R18", "car_235_40_R18", "car_235_45_R18", "car_235_50_R18", "car_235_50_R18", "car_235_55_R17", "car_245_45_R18", "car_245_45_R18", "car_245_45_R18", "car_255_45_R18", "car_225_40_R19", "car_225_45_R17", "car_245_45_R19", "car_245_50_R18", "car_255_35_R18", "car_275_40_R19", "car_225_40_R18", "car_245_50_R18", "car_215_55_R17", "car_205_70_R15", "car_215_65_R16", "car_215_70_R15", "car_215_70_R16", "car_225_60_R18", "car_225_65_R17", "car_235_55_R20", "car_235_60_R16", "car_235_60_R17", "car_235_60_R18", "car_235_65_R17", "car_235_65_R18", "car_235_70_R16", "car_245_50_R20", "car_245_55_R19", "car_245_60_R18", "car_245_65_R17", "car_255_55_R19", "car_255_65_R17", "car_265_60_R18", "car_265_70_R16", "car_265_70_R17", "car_265_70_R18",])
                    function isSizeValid(size) {
                        for (let item of validSizes) { if (item.startsWith(size)) { return true; } }
                        return false
                    }
                    function isRinValid(size) {
                        for (let item of validSizes) { if (item.localeCompare(size) == 0) { return true; } }
                        return false
                    }
                    function setDefaults() {
                        let pageTitle = ""
                        var parts = ["car", "205", "55", "R16"]
                        if (pageTitle.split("_").length == 4) { var parts = pageTitle.split("_") }
                        document.getElementById("vehicle-select").value = parts[0]; document.getElementById("vehicle-select").onchange(); document.getElementById("width-select").value = parts[1]; document.getElementById("width-select").onchange(); document.getElementById("height-select").value = parts[2]; document.getElementById("height-select").onchange(); document.getElementById("rin-select").value = parts[3].toUpperCase(); document.getElementById("btn-tires-form").disabled = false;
                    }
                    window.onload = setDefaults()
                    function onVehicleSelectChanged() {
                        document.getElementById("btn-tires-form").disabled = true; let selectedVehicleType = document.getElementById("vehicle-select").value; let select = document.getElementById("width-select")
                        let height = document.getElementById("height-select")
                        let rin = document.getElementById("rin-select")
                        for (let option of select.options) { let sizePrefix = selectedVehicleType + "_" + option.value + "_"; option.disabled = !isSizeValid(sizePrefix); option.style.display = (option.disabled ? "none" : "block") }
                        select.value = null
                        height.value = null
                        rin.value = null
                    }
                    function onWidthSelectChanged() {
                        document.getElementById("btn-tires-form").disabled = true; let selectedVehicleType = document.getElementById("vehicle-select").value; let selectedWidth = document.getElementById("width-select").value; let select = document.getElementById("height-select")
                        for (let option of select.options) { let sizePrefix = selectedVehicleType + "_" + selectedWidth + "_" + option.value + "_"; option.disabled = !isSizeValid(sizePrefix); option.style.display = (option.disabled ? "none" : "block") }
                        select.value = null
                    }
                    function onHeightSelectChanged() {
                        document.getElementById("btn-tires-form").disabled = true; let selectedVehicleType = document.getElementById("vehicle-select").value; let selectedWidth = document.getElementById("width-select").value; let selectedHeight = document.getElementById("height-select").value; let select = document.getElementById("rin-select")
                        for (let option of select.options) { let sizePrefix = selectedVehicleType + "_" + selectedWidth + "_" + selectedHeight + "_" + option.value; option.disabled = !isRinValid(sizePrefix); option.style.display = (option.disabled ? "none" : "block") }
                        select.value = null
                    }
                    function onRinSelectChanged() { document.getElementById("btn-tires-form").disabled = false; }
                    function onSearchFormSubmit() { let selectedVehicleType = document.getElementById("vehicle-select").value; let width = document.getElementById("width-select").value; let height = document.getElementById("height-select").value; let rin = document.getElementById("rin-select").value; window.location.href = "/medidas/" + selectedVehicleType + "_" + width + "_" + height + "_" + rin.toLowerCase(); }</script>
            </div>
            </section>
